<Type Name="KeywordTokenizer" FullName="Microsoft.Azure.Search.Models.KeywordTokenizer">
  <TypeSignature Language="C#" Value="public class KeywordTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeywordTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.KeywordTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class KeywordTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type KeywordTokenizer = class&#xA;    inherit Tokenizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Tokenizer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.KeywordTokenizer")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Obsolete("This type is obsolete. Please use KeywordTokenizerV2 instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1c442-101">Gibt die gesamte Eingabe als einzelnes Token aus.</span><span class="sxs-lookup"><span data-stu-id="1c442-101">Emits the entire input as a single token.</span></span> <span data-ttu-id="1c442-102">Diese Tokenizer wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="1c442-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/KeywordTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeywordTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordTokenizer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c442-103">Initialisiert eine neue Instanz der KeywordTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1c442-103">Initializes a new instance of the KeywordTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeywordTokenizer (string name, Nullable&lt;int&gt; bufferSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; bufferSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordTokenizer.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional bufferSize As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.KeywordTokenizer : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.KeywordTokenizer" Usage="new Microsoft.Azure.Search.Models.KeywordTokenizer (name, bufferSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="bufferSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="bufferSize">To be added.</param>
        <summary>
            <span data-ttu-id="1c442-104">Initialisiert eine neue Instanz der KeywordTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1c442-104">Initializes a new instance of the KeywordTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.KeywordTokenizer.BufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BufferSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.KeywordTokenizer.BufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bufferSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c442-105">Ruft ab oder legt die Größe des Lesepuffers in Bytes fest.</span><span class="sxs-lookup"><span data-stu-id="1c442-105">Gets or sets the read buffer size in bytes.</span></span> <span data-ttu-id="1c442-106">Standardwert ist 256.</span><span class="sxs-lookup"><span data-stu-id="1c442-106">Default is 256.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="keywordTokenizer.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c442-107">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1c442-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1c442-108">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1c442-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>