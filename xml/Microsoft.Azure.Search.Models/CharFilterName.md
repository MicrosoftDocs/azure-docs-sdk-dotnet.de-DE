<Type Name="CharFilterName" FullName="Microsoft.Azure.Search.Models.CharFilterName">
  <TypeSignature Language="C#" Value="public sealed class CharFilterName : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CharFilterName extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CharFilterName" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CharFilterName&#xA;Inherits ExtensibleEnum(Of CharFilterName)" />
  <TypeSignature Language="F#" Value="type CharFilterName = class&#xA;    inherit ExtensibleEnum&lt;CharFilterName&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.CharFilterName</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ecb7f-101">Definiert die Namen aller Zeichen Filter, die von Azure Search unterstützt.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-101">Defines the names of all character filters supported by Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.CharFilterName Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.CharFilterName Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CharFilterName.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As CharFilterName" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.CharFilterName" Usage="Microsoft.Azure.Search.Models.CharFilterName.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.CharFilterName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ecb7f-102">Der Name des Filters Zeichen.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-102">Name of the character filter.</span></span></param>
        <summary>
            <span data-ttu-id="ecb7f-103">Erstellt eine neue Instanz der CharFilterName, oder gibt eine vorhandene Instanz zurück, wenn es sich bei dem angegebenen Namen, die mit der einen bekannten Zeichen Filter übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-103">Creates a new CharFilterName instance, or returns an existing instance if the given name matches that of a known character filter.</span></span>
            </summary>
        <returns><span data-ttu-id="ecb7f-104">Eine CharFilterName-Instanz mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-104">A CharFilterName instance with the given name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HtmlStrip">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.CharFilterName HtmlStrip;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.CharFilterName HtmlStrip" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.CharFilterName.HtmlStrip" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly HtmlStrip As CharFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable HtmlStrip : Microsoft.Azure.Search.Models.CharFilterName" Usage="Microsoft.Azure.Search.Models.CharFilterName.HtmlStrip" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.CharFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecb7f-105">Filter, der versucht, das Entfernen von HTML-Zeichen erstellt.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-105">A character filter that attempts to strip out HTML constructs.</span></span>
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/charfilter/HTMLStripCharFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.CharFilterName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.CharFilterName op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CharFilterName.op_Implicit(System.String)~Microsoft.Azure.Search.Models.CharFilterName" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As CharFilterName" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.CharFilterName" Usage="Microsoft.Azure.Search.Models.CharFilterName.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.CharFilterName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ecb7f-106">zu konvertierende Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-106">string to convert.</span></span></param>
        <summary>
            <span data-ttu-id="ecb7f-107">Definiert die implizite Konvertierung von Zeichenfolgen in CharFilterName.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-107">Defines implicit conversion from string to CharFilterName.</span></span>
            </summary>
        <returns><span data-ttu-id="ecb7f-108">Die Zeichenfolge als eine CharFilterName.</span><span class="sxs-lookup"><span data-stu-id="ecb7f-108">The string as a CharFilterName.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>