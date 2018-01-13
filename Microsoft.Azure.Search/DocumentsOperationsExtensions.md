<Type Name="DocumentsOperationsExtensions" FullName="Microsoft.Azure.Search.DocumentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DocumentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DocumentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.DocumentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DocumentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DocumentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Vorgänge zum Abfragen von Index und hochladen, Zusammenführen und Löschen von Dokumenten.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult ContinueSearch (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult ContinueSearch(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ContinueSearch : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch (operations, continuationToken, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="continuationToken">
            Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="ContinueSearch&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt; ContinueSearch&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt; ContinueSearch&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ContinueSearch : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch (operations, continuationToken, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="continuationToken">
            Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="ContinueSearchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt; ContinueSearchAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt; ContinueSearchAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ContinueSearchAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync (operations, continuationToken, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;ContinueSearchAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="continuationToken">
            Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="ContinueSearchAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt; ContinueSearchAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt; ContinueSearchAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ContinueSearchAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync (operations, continuationToken, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;ContinueSearchAsync&gt;d__5`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="continuationToken">
            Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public static long Count (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int64 Count(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Count(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Count : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; int64" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Count (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Fragt die Anzahl der Dokumente in der Azure Search-Index.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;long&gt; CountAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int64&gt; CountAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.CountAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CountAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.CountAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;CountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Document Get (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Document Get(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Get(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Document" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Get (operations, key, selectedFields, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Document</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="key">
            Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.
            </param>
        <param name="selectedFields">
            Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen werden aus dem zurückgegebenen Dokument fehlt. Alle abrufbar Felder sind standardmäßig im Resultset enthalten.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft ein Dokument aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            Das angeforderte Dokument.
            </returns>
        <remarks>
            Die nicht generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T Get&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T Get&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Get``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; 'T (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Get (operations, key, selectedFields, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="key">
            Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.
            </param>
        <param name="selectedFields">
            Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen müssen Null oder Default als die entsprechenden Eigenschaftswert im zurückgegebenen Objekt. Alle abrufbar Felder sind standardmäßig im Resultset enthalten.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft ein Dokument aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            Das angeforderte Dokument.
            </returns>
        <remarks>
            Generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt; GetAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Document&gt; GetAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync (operations, key, selectedFields, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="key">
            Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.
            </param>
        <param name="selectedFields">
            Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen werden aus dem zurückgegebenen Dokument fehlt.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein Dokument aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            Das angeforderte Dokument.
            </returns>
        <remarks>
            Die nicht generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen. Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;T&gt; GetAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!T&gt; GetAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync (operations, key, selectedFields, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;GetAsync&gt;d__9`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="key">
            Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.
            </param>
        <param name="selectedFields">
            Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen müssen Null oder Default als die entsprechenden Eigenschaftswert im zurückgegebenen Objekt. Alle abrufbar Felder sind standardmäßig im Resultset enthalten.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein Dokument aus dem Azure-Suchindex ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            Das angeforderte Dokument.
            </returns>
        <remarks>
            Generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Index">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentIndexResult Index (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentIndexResult Index(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Index(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Index : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Index (operations, batch, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentIndexResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="batch">
            Der Batch, der indexaktionen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="Index&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentIndexResult Index&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentIndexResult Index&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Index``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Index : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Index (operations, batch, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentIndexResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="batch">
            Der Batch, der indexaktionen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.
            </returns>
        <remarks>
            Generische Überladung von Index und IndexAsync Methoden unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert. Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist. Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft. Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IndexAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync (operations, batch, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;IndexAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="batch">
            Der Batch, der indexaktionen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="IndexAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IndexAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync (operations, batch, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;IndexAsync&gt;d__13`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="batch">
            Der Batch, der indexaktionen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
            Generische Überladung von Index und IndexAsync Methoden unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert. Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist. Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft. Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult Search (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult Search(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Search(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Search : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Search (operations, searchText, searchParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchText">
            Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen. Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.
            </param>
        <param name="searchParameters">
            Parameter für die Suchabfrage verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="Search&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt; Search&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt; Search&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Search``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Search : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Search (operations, searchText, searchParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchText">
            Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen. Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.
            </param>
        <param name="searchParameters">
            Parameter für die Suchabfrage verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="SearchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt; SearchAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt; SearchAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SearchAsync : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync (operations, searchText, searchParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SearchAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchText">
            Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen. Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.
            </param>
        <param name="searchParameters">
            Parameter für die Suchabfrage verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="SearchAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt; SearchAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt; SearchAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SearchAsync : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync (operations, searchText, searchParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SearchAsync&gt;d__17`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchText">
            Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen. Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.
            </param>
        <param name="searchParameters">
            Parameter für die Suchabfrage verfeinern.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
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
    <Member MemberName="Suggest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSuggestResult Suggest (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSuggestResult Suggest(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Suggest : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSuggestResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest (operations, searchText, suggesterName, suggestParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSuggestResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
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
    <Member MemberName="Suggest&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt; Suggest&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt; Suggest&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Suggest : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest (operations, searchText, suggesterName, suggestParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
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
    <Member MemberName="SuggestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt; SuggestAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt; SuggestAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuggestAsync : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync (operations, searchText, suggesterName, suggestParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SuggestAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
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
    <Member MemberName="SuggestAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt; SuggestAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt; SuggestAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuggestAsync : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync (operations, searchText, suggesterName, suggestParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SuggestAsync&gt;d__21`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
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