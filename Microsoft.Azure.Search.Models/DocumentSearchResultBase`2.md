<Type Name="DocumentSearchResultBase&lt;TResult,TDoc&gt;" FullName="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;TResult,TDoc&gt;">
  <TypeSignature Language="C#" Value="public class DocumentSearchResultBase&lt;TResult,TDoc&gt; where TResult : SearchResultBase&lt;TDoc&gt; where TDoc : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentSearchResultBase`2&lt;(class Microsoft.Azure.Search.Models.SearchResultBase`1&lt;!TDoc&gt;) TResult, class TDoc&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentSearchResultBase(Of TResult, TDoc)" />
  <TypeSignature Language="F#" Value="type DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResult">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.SearchResultBase&lt;TDoc&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TDoc">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TResult">
            Der Typ der Skriptobjektmodell-Klasse, die Dokumente in einer Suchantwort kapselt.
            </typeparam>
    <typeparam name="TDoc">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
    <summary>
            Antwort mit der Suche ergibt sich aus einem Azure Search-Index.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentSearchResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SearchContinuationToken ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.SearchContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As SearchContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.Azure.Search.Models.SearchContinuationToken with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SearchContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ein Fortsetzungstoken an, die verwendet wird, um den Vorgang fortzusetzen, Abrufen von Suchergebnissen an. Dies ist erforderlich, wenn eine suchanforderung mit einer einzigen Antwort von Azure Search entsprochen werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Diese Eigenschaft ist null, es sei denn, die Azure Search alle angeforderten Dokumente in einer einzelnen Suche Antwort zurückgeben kann. Das kann verschiedene Gründe sind implementierungsspezifisch und unterliegt Änderungen auftreten.
            Stabile Clients sollten für die Behandlung von Fällen bereit sein, in denen weniger Dokumente als erwartet zurückgegeben werden und ein Fortsetzungstoken zum Abrufen von Dokumenten enthalten ist. Wenn diese Eigenschaft nicht null ist, können Sie dessen Wert übergeben der <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">ContinueSearchAsync</c> Methode, um weitere Suchergebnisse abzurufen.
            </para>
          <para>
            Beachten Sie, dass diese Eigenschaft nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren. Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter zu suchen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gesamtzahl der Ergebnisse ab, durch den Suchvorgang gefunden, oder null, wenn die Anzahl die nicht angefordert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>
            Falls vorhanden, möglicherweise die Anzahl größer als die Anzahl von Ergebnissen in dieser Antwort. Dies kann geschehen, wenn Sie mithilfe der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> oder <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> Parameter, oder wenn Azure Search alle angeforderten Dokumente in einer einzelnen Suche Antwort zurückgeben kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Coverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Coverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Coverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Coverage" />
      <MemberSignature Language="VB.NET" Value="Public Property Coverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Coverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Coverage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, der des Prozentsatz des Indexes, der in der Abfrage enthalten, null oder, wenn MinimumCoverage nicht festgelegt wurde, der <c cref="T:Microsoft.Azure.Search.Models.SearchParameters">SearchParameters</c>.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FacetResults Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.FacetResults Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As FacetResults" />
      <MemberSignature Language="F#" Value="member this.Facets : Microsoft.Azure.Search.Models.FacetResults with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Facets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FacetResults</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Facet Abfrageergebnisse für den Suchvorgang oder Null, wenn die Abfrage keine Facets Ausdrücke enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;TResult&gt; Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;!TResult&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IList(Of TResult)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;'Result (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt;)&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sequenz der von der Abfrage zurückgegebenen Ergebnisse ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>