<Type Name="IndexBatch&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class IndexBatch&lt;T&gt; : Microsoft.Azure.Search.Models.IndexBatchBase&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;,T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexBatch`1&lt;class T&gt; extends Microsoft.Azure.Search.Models.IndexBatchBase`2&lt;class Microsoft.Azure.Search.Models.IndexAction`1&lt;!T&gt;, !T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexBatch`1" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexBatch(Of T)&#xA;Inherits IndexBatchBase(Of IndexAction(Of T), T)" />
  <TypeSignature Language="F#" Value="type IndexBatch&lt;'T (requires 'T : null)&gt; = class&#xA;    inherit IndexBatchBase&lt;IndexAction&lt;'T&gt;, 'T (requires 'T : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.IndexBatchBase&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;,T&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TAction">Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TDoc">T</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            <span data-ttu-id="9aa0f-101">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9aa0f-101">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="9aa0f-102">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="9aa0f-102">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="9aa0f-103">Enthält einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen zum Senden an den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="9aa0f-103">Contains a batch of upload, merge, and/or delete actions to send to the Azure Search index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Search.Models.IndexAction`1&lt;!T&gt;&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatch`1.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.Search.Models.IndexAction{`0}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (actions As IEnumerable(Of IndexAction(Of T)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; : seq&lt;Microsoft.Azure.Search.Models.IndexAction&lt;'T&gt;&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; actions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="actions"><span data-ttu-id="9aa0f-104">Die indexaktionen in den Batch aufgenommen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9aa0f-104">The index actions to include in the batch.</span></span></param>
        <summary>
            <span data-ttu-id="9aa0f-105">Initialisiert eine neue Instanz der IndexBatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9aa0f-105">Initializes a new instance of the IndexBatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>