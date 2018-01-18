<Type Name="TokenInfo" FullName="Microsoft.Azure.Search.Models.TokenInfo">
  <TypeSignature Language="C#" Value="public class TokenInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TokenInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TokenInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenInfo" />
  <TypeSignature Language="F#" Value="type TokenInfo = class" />
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
            <span data-ttu-id="627c5-101">Informationen zu einem zurückgegebene Token über einen Analyzer.</span><span class="sxs-lookup"><span data-stu-id="627c5-101">Information about a token returned by an analyzer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenInfo.#ctor" />
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
            <span data-ttu-id="627c5-102">Initialisiert eine neue Instanz der TokenInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="627c5-102">Initializes a new instance of the TokenInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInfo (string token = null, Nullable&lt;int&gt; startOffset = null, Nullable&lt;int&gt; endOffset = null, Nullable&lt;int&gt; position = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string token, valuetype System.Nullable`1&lt;int32&gt; startOffset, valuetype System.Nullable`1&lt;int32&gt; endOffset, valuetype System.Nullable`1&lt;int32&gt; position) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenInfo.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional token As String = null, Optional startOffset As Nullable(Of Integer) = null, Optional endOffset As Nullable(Of Integer) = null, Optional position As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.TokenInfo : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.TokenInfo" Usage="new Microsoft.Azure.Search.Models.TokenInfo (token, startOffset, endOffset, position)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="startOffset" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="endOffset" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="position" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="627c5-103">Das zurückgegebene Token über die Analyzer.</span><span class="sxs-lookup"><span data-stu-id="627c5-103">The token returned by the analyzer.</span></span></param>
        <param name="startOffset"><span data-ttu-id="627c5-104">Der Index des ersten Zeichens des Tokens im Eingabetext an.</span><span class="sxs-lookup"><span data-stu-id="627c5-104">The index of the first character of the token in the input text.</span></span></param>
        <param name="endOffset"><span data-ttu-id="627c5-105">Der Index des letzten Zeichens des Tokens im Eingabetext an.</span><span class="sxs-lookup"><span data-stu-id="627c5-105">The index of the last character of the token in the input text.</span></span></param>
        <param name="position"><span data-ttu-id="627c5-106">Die Position des Tokens im Eingabetext relativ zu anderen Token.</span><span class="sxs-lookup"><span data-stu-id="627c5-106">The position of the token in the input text relative to other tokens.</span></span> <span data-ttu-id="627c5-107">Das erste Token in der Eingabetext hat Position 0, der nächsten Position 1 und So weiter.</span><span class="sxs-lookup"><span data-stu-id="627c5-107">The first token in the input text has position 0, the next has position 1, and so on.</span></span> <span data-ttu-id="627c5-108">Je nach den Analyzer, die verwendet wird möglicherweise einige Token derselben Position, z. B. Wenn sie die Synonyme zueinander sind.</span><span class="sxs-lookup"><span data-stu-id="627c5-108">Depending on the analyzer used, some tokens might have the same position, for example if they are synonyms of each other.</span></span></param>
        <summary>
            <span data-ttu-id="627c5-109">Initialisiert eine neue Instanz der TokenInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="627c5-109">Initializes a new instance of the TokenInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EndOffset { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EndOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.EndOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property EndOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EndOffset : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.EndOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627c5-110">Ruft den Index des letzten Zeichens des Tokens im Eingabetext an.</span><span class="sxs-lookup"><span data-stu-id="627c5-110">Gets the index of the last character of the token in the input text.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Position { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.Position" />
      <MemberSignature Language="VB.NET" Value="Public Property Position As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Position : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="position")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627c5-111">Ruft die Position des Tokens im Eingabetext relativ zu anderen Token ab.</span><span class="sxs-lookup"><span data-stu-id="627c5-111">Gets the position of the token in the input text relative to other tokens.</span></span> <span data-ttu-id="627c5-112">Das erste Token in der Eingabetext hat Position 0, der nächsten Position 1 und So weiter.</span><span class="sxs-lookup"><span data-stu-id="627c5-112">The first token in the input text has position 0, the next has position 1, and so on.</span></span> <span data-ttu-id="627c5-113">Je nach den Analyzer, die verwendet wird möglicherweise einige Token derselben Position, z. B. Wenn sie die Synonyme zueinander sind.</span><span class="sxs-lookup"><span data-stu-id="627c5-113">Depending on the analyzer used, some tokens might have the same position, for example if they are synonyms of each other.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StartOffset { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property StartOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StartOffset : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627c5-114">Ruft den Index des ersten Zeichens des Tokens im Eingabetext an.</span><span class="sxs-lookup"><span data-stu-id="627c5-114">Gets the index of the first character of the token in the input text.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627c5-115">Ruft das zurückgegebene Token über die Analyzer ab.</span><span class="sxs-lookup"><span data-stu-id="627c5-115">Gets the token returned by the analyzer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>