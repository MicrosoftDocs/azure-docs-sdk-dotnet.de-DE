<Type Name="DocumentSuggestResultBase&lt;TResult,TDoc&gt;" FullName="Microsoft.Azure.Search.Models.DocumentSuggestResultBase&lt;TResult,TDoc&gt;">
  <TypeSignature Language="C#" Value="public class DocumentSuggestResultBase&lt;TResult,TDoc&gt; where TResult : SuggestResultBase&lt;TDoc&gt; where TDoc : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentSuggestResultBase`2&lt;(class Microsoft.Azure.Search.Models.SuggestResultBase`1&lt;!TDoc&gt;) TResult, class TDoc&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentSuggestResultBase`2" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentSuggestResultBase(Of TResult, TDoc)" />
  <TypeSignature Language="F#" Value="type DocumentSuggestResultBase&lt;'Result, 'Doc (requires 'Result :&gt; SuggestResultBase&lt;'Doc&gt; and 'Doc : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResult">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.SuggestResultBase&lt;TDoc&gt;</BaseTypeName>
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
            <span data-ttu-id="a06c8-101">Der Typ der Skriptobjektmodell-Klasse, die Dokumente in einer Antwort Vorschlag kapselt.</span><span class="sxs-lookup"><span data-stu-id="a06c8-101">Type of the model class that encapsulates documents in a suggestion response.</span></span>
            </typeparam>
    <typeparam name="TDoc">
            <span data-ttu-id="a06c8-102">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a06c8-102">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="a06c8-103">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a06c8-103">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="a06c8-104">Antwort mit vorschlagsabfrage ergibt sich aus einem Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="a06c8-104">Response containing suggestion query results from an Azure Search index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentSuggestResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentSuggestResultBase`2.#ctor" />
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
    <Member MemberName="Coverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Coverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Coverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSuggestResultBase`2.Coverage" />
      <MemberSignature Language="VB.NET" Value="Public Property Coverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Coverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSuggestResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SuggestResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Coverage" />
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
            <span data-ttu-id="a06c8-105">Ruft einen Wert, der angibt, der des Prozentsatz des Indexes, der in der Abfrage enthalten, null oder, wenn MinimumCoverage nicht festgelegt wurde, der <c cref="T:Microsoft.Azure.Search.Models.SuggestParameters">SuggestParameters</c>.</span><span class="sxs-lookup"><span data-stu-id="a06c8-105">Gets a value indicating the percentage of the index that was included in the query, or null if MinimumCoverage was not set in the <c cref="T:Microsoft.Azure.Search.Models.SuggestParameters">SuggestParameters</c>.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;TResult&gt; Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;!TResult&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSuggestResultBase`2.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IList(Of TResult)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;'Result (requires 'Result :&gt; Microsoft.Azure.Search.Models.SuggestResultBase&lt;'Doc&gt;)&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSuggestResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SuggestResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Results" />
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
            <span data-ttu-id="a06c8-106">Ruft die Sequenz der von der Abfrage zurückgegebenen Ergebnisse ab.</span><span class="sxs-lookup"><span data-stu-id="a06c8-106">Gets the sequence of results returned by the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>