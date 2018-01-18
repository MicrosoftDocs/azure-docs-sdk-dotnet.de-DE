<Type Name="AsciiFoldingTokenFilter" FullName="Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter">
  <TypeSignature Language="C#" Value="public class AsciiFoldingTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AsciiFoldingTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class AsciiFoldingTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type AsciiFoldingTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.AsciiFoldingTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ada92-101">Alphabetische, numerische und symbolische Unicode-Zeichen, die nicht in der ersten 127 ASCII-Zeichen ("Lateinischen" Unicode-Block) sind konvertiert in ihre ASCII-Entsprechungen, wenn solche Entsprechungen vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="ada92-101">Converts alphabetic, numeric, and symbolic Unicode characters which are not in the first 127 ASCII characters (the "Basic Latin" Unicode block) into their ASCII equivalents, if such equivalents exist.</span></span> <span data-ttu-id="ada92-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="ada92-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ASCIIFoldingFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsciiFoldingTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter.#ctor" />
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
            <span data-ttu-id="ada92-103">Initialisiert eine neue Instanz der AsciiFoldingTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ada92-103">Initializes a new instance of the AsciiFoldingTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsciiFoldingTokenFilter (string name, Nullable&lt;bool&gt; preserveOriginal = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; preserveOriginal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional preserveOriginal As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter" Usage="new Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter (name, preserveOriginal)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="preserveOriginal" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ada92-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="ada92-104">The name of the token filter.</span></span> <span data-ttu-id="ada92-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="ada92-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="preserveOriginal"><span data-ttu-id="ada92-106">Ein Wert, der angibt, ob das ursprüngliche Token beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ada92-106">A value indicating whether the original token will be kept.</span></span> <span data-ttu-id="ada92-107">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="ada92-107">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="ada92-108">Initialisiert eine neue Instanz der AsciiFoldingTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ada92-108">Initializes a new instance of the AsciiFoldingTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveOriginal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreserveOriginal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreserveOriginal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter.PreserveOriginal" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveOriginal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreserveOriginal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter.PreserveOriginal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveOriginal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ada92-109">Ruft ab oder legt einen Wert, der angibt, ob das ursprüngliche Token beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="ada92-109">Gets or sets a value indicating whether the original token will be kept.</span></span> <span data-ttu-id="ada92-110">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="ada92-110">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AsciiFoldingTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="asciiFoldingTokenFilter.Validate " />
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
            <span data-ttu-id="ada92-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ada92-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ada92-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ada92-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>