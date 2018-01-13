<Type Name="DocumentSuggestResult&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class DocumentSuggestResult&lt;T&gt; : Microsoft.Azure.Search.Models.DocumentSuggestResultBase&lt;Microsoft.Azure.Search.Models.SuggestResult&lt;T&gt;,T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentSuggestResult`1&lt;class T&gt; extends Microsoft.Azure.Search.Models.DocumentSuggestResultBase`2&lt;class Microsoft.Azure.Search.Models.SuggestResult`1&lt;!T&gt;, !T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentSuggestResult`1" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentSuggestResult(Of T)&#xA;Inherits DocumentSuggestResultBase(Of SuggestResult(Of T), T)" />
  <TypeSignature Language="F#" Value="type DocumentSuggestResult&lt;'T (requires 'T : null)&gt; = class&#xA;    inherit DocumentSuggestResultBase&lt;SuggestResult&lt;'T&gt;, 'T (requires 'T : null)&gt;" />
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
    <BaseTypeName>Microsoft.Azure.Search.Models.DocumentSuggestResultBase&lt;Microsoft.Azure.Search.Models.SuggestResult&lt;T&gt;,T&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TResult">Microsoft.Azure.Search.Models.SuggestResult&lt;T&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TDoc">T</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.
            </typeparam>
    <summary>
            Antwort mit vorschlagsabfrage ergibt sich aus einem Azure Search-Index.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentSuggestResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentSuggestResult`1.#ctor" />
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
  </Members>
</Type>