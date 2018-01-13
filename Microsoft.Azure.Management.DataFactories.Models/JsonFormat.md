<Type Name="JsonFormat" FullName="Microsoft.Azure.Management.DataFactories.Models.JsonFormat">
  <TypeSignature Language="C#" Value="public class JsonFormat : Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonFormat extends Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonFormat&#xA;Inherits StorageFormat" />
  <TypeSignature Language="F#" Value="type JsonFormat = class&#xA;    inherit StorageFormat" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ca0d8-101">Die Daten im JSON-Format gespeichert.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-101">The data stored in JSON format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public string EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As String" />
      <MemberSignature Language="F#" Value="member this.EncodingName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.EncodingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0d8-102">Der Codepagename der bevorzugten Codierung.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-102">The code page name of the preferred encoding.</span></span> <span data-ttu-id="ca0d8-103">Wenn nicht angegeben ist, ist der Standardwert "Utf-8", es sei denn, einer anderen Codierung von Unicode-Byte-reihenfolgemarkierung (BOM) bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-103">If not provided, the default value is "utf-8", unless the byte order mark (BOM) denotes another Unicode encoding.</span></span> <span data-ttu-id="ca0d8-104">Die vollständige Liste der unterstützten Werte finden Sie in der Spalte "Name" der Tabelle der Codierungen in den folgenden Verweis: https://msdn.microsoft.com/library/system.text.encoding.aspx#Anchor_5.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-104">The full list of supported values can be found in the "Name" column of the table of encodings in the following reference: https://msdn.microsoft.com/library/system.text.encoding.aspx#Anchor_5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0d8-105">Der JSON Dateimuster.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-105">File pattern of JSON.</span></span> <span data-ttu-id="ca0d8-106">Genauer gesagt die Methode zum Trennen von einzelnen JSON-Objekts sein.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-106">To be more specific, the way of separating single JSON object.</span></span> <span data-ttu-id="ca0d8-107">Muss einer der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormatFilePattern" />.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-107">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormatFilePattern" />.</span></span>
            <span data-ttu-id="ca0d8-108">Standardwert ist "SetOfObjects".</span><span class="sxs-lookup"><span data-stu-id="ca0d8-108">Default value is "setOfObjects".</span></span>
            <span data-ttu-id="ca0d8-109">Es wird die Groß-/Kleinschreibung beachtet.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-109">It is case-sensitive.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonNodeReference">
      <MemberSignature Language="C#" Value="public string JsonNodeReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JsonNodeReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonNodeReference" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonNodeReference As String" />
      <MemberSignature Language="F#" Value="member this.JsonNodeReference : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonNodeReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0d8-110">Optional.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-110">Optional.</span></span> <span data-ttu-id="ca0d8-111">Die JSONPath des JSON-Array-Knotens, vereinfacht werden.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-111">The JSONPath of the JSON array node to be flattened.</span></span> <span data-ttu-id="ca0d8-112">Referenz: http://goessner.net/articles/JsonPath/.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-112">Reference: http://goessner.net/articles/JsonPath/.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPathDefinition">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; JsonPathDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; JsonPathDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonPathDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPathDefinition As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.JsonPathDefinition : System.Collections.Generic.Dictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonPathDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0d8-113">Optional.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-113">Optional.</span></span> <span data-ttu-id="ca0d8-114">Die Definition der relativen JSONPath in die ursprünglichen JSON-Objekte für die entsprechenden Spalte in der konvertierten Zeile beim Konvertieren von JSON-Objekten auf Zeilen.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-114">The definition of the relative JSONPath in the original JSON objects for the targeted column in the converted row when converting JSON objects to rows.</span></span> <span data-ttu-id="ca0d8-115">Beispiel: {"Column1": "$. Column1Path"}.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-115">Example: { "Column1": "$.Column1Path"}.</span></span> <span data-ttu-id="ca0d8-116">Die JSONPath der Stamm-Elemente muss mit einem "$"-Zeichens starten.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-116">The JSONPath of the root items must start with a "$" character.</span></span> <span data-ttu-id="ca0d8-117">Alle anderen Elemente im vereinfachten von JsonNodeReference definierten Array darf nicht aus.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-117">All the other items in the flattened array defined by JsonNodeReference must not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestingSeparator">
      <MemberSignature Language="C#" Value="public string NestingSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NestingSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.NestingSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property NestingSeparator As String" />
      <MemberSignature Language="F#" Value="member this.NestingSeparator : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.NestingSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0d8-118">Das Zeichen zum Trennen der Schachtelungsebenen verwendet.</span><span class="sxs-lookup"><span data-stu-id="ca0d8-118">The character used to separate nesting levels.</span></span> <span data-ttu-id="ca0d8-119">Standardwert ist "." (Punkt).</span><span class="sxs-lookup"><span data-stu-id="ca0d8-119">Default value is "." (dot).</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>