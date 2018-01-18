<Type Name="LimitTokenFilter" FullName="Microsoft.Azure.Search.Models.LimitTokenFilter">
  <TypeSignature Language="C#" Value="public class LimitTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LimitTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.LimitTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class LimitTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type LimitTokenFilter = class&#xA;    inherit TokenFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.TokenFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.LimitTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b15fb-101">Schränkt die Anzahl der Token beim indizieren.</span><span class="sxs-lookup"><span data-stu-id="b15fb-101">Limits the number of tokens while indexing.</span></span> <span data-ttu-id="b15fb-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="b15fb-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LimitTokenCountFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LimitTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LimitTokenFilter.#ctor" />
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
            <span data-ttu-id="b15fb-103">Initialisiert eine neue Instanz der LimitTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b15fb-103">Initializes a new instance of the LimitTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LimitTokenFilter (string name, Nullable&lt;int&gt; maxTokenCount = null, Nullable&lt;bool&gt; consumeAllTokens = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenCount, valuetype System.Nullable`1&lt;bool&gt; consumeAllTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LimitTokenFilter.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenCount As Nullable(Of Integer) = null, Optional consumeAllTokens As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.LimitTokenFilter : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.LimitTokenFilter" Usage="new Microsoft.Azure.Search.Models.LimitTokenFilter (name, maxTokenCount, consumeAllTokens)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="consumeAllTokens" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="b15fb-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="b15fb-104">The name of the token filter.</span></span> <span data-ttu-id="b15fb-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="b15fb-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="maxTokenCount"><span data-ttu-id="b15fb-106">Die maximale Anzahl der Token zu erzeugen.</span><span class="sxs-lookup"><span data-stu-id="b15fb-106">The maximum number of tokens to produce.</span></span> <span data-ttu-id="b15fb-107">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="b15fb-107">Default is 1.</span></span></param>
        <param name="consumeAllTokens"><span data-ttu-id="b15fb-108">Ein Wert, der angibt, ob alle Token aus der Eingabe verarbeitet werden müssen, auch wenn MaxTokenCount erreicht wird.</span><span class="sxs-lookup"><span data-stu-id="b15fb-108">A value indicating whether all tokens from the input must be consumed even if maxTokenCount is reached.</span></span> <span data-ttu-id="b15fb-109">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="b15fb-109">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="b15fb-110">Initialisiert eine neue Instanz der LimitTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b15fb-110">Initializes a new instance of the LimitTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumeAllTokens">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ConsumeAllTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ConsumeAllTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.LimitTokenFilter.ConsumeAllTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumeAllTokens As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ConsumeAllTokens : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.LimitTokenFilter.ConsumeAllTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="consumeAllTokens")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b15fb-111">Ruft ab oder legt einen Wert, der angibt, ob alle Token aus der Eingabe verarbeitet werden müssen, auch wenn MaxTokenCount erreicht wird.</span><span class="sxs-lookup"><span data-stu-id="b15fb-111">Gets or sets a value indicating whether all tokens from the input must be consumed even if maxTokenCount is reached.</span></span> <span data-ttu-id="b15fb-112">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="b15fb-112">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.LimitTokenFilter.MaxTokenCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.LimitTokenFilter.MaxTokenCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b15fb-113">Ruft ab oder legt die maximale Anzahl der Token zu erzeugen.</span><span class="sxs-lookup"><span data-stu-id="b15fb-113">Gets or sets the maximum number of tokens to produce.</span></span> <span data-ttu-id="b15fb-114">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="b15fb-114">Default is 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LimitTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="limitTokenFilter.Validate " />
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
            <span data-ttu-id="b15fb-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b15fb-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b15fb-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b15fb-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>