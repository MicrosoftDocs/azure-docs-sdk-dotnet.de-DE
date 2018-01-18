<Type Name="UniqueTokenFilter" FullName="Microsoft.Azure.Search.Models.UniqueTokenFilter">
  <TypeSignature Language="C#" Value="public class UniqueTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UniqueTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.UniqueTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class UniqueTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type UniqueTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.UniqueTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c28b3-101">Filtert-Token mit den gleichen Text wie der vorherige Token.</span><span class="sxs-lookup"><span data-stu-id="c28b3-101">Filters out tokens with same text as the previous token.</span></span> <span data-ttu-id="c28b3-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="c28b3-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/RemoveDuplicatesTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniqueTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.UniqueTokenFilter.#ctor" />
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
            <span data-ttu-id="c28b3-103">Initialisiert eine neue Instanz der UniqueTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c28b3-103">Initializes a new instance of the UniqueTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniqueTokenFilter (string name, Nullable&lt;bool&gt; onlyOnSamePosition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; onlyOnSamePosition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.UniqueTokenFilter.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional onlyOnSamePosition As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.UniqueTokenFilter : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.UniqueTokenFilter" Usage="new Microsoft.Azure.Search.Models.UniqueTokenFilter (name, onlyOnSamePosition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="onlyOnSamePosition" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c28b3-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="c28b3-104">The name of the token filter.</span></span> <span data-ttu-id="c28b3-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="c28b3-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="onlyOnSamePosition"><span data-ttu-id="c28b3-106">Ein Wert, der angibt, ob Duplikate nur an der gleichen Position zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="c28b3-106">A value indicating whether to remove duplicates only at the same position.</span></span> <span data-ttu-id="c28b3-107">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="c28b3-107">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="c28b3-108">Initialisiert eine neue Instanz der UniqueTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c28b3-108">Initializes a new instance of the UniqueTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnlyOnSamePosition">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OnlyOnSamePosition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OnlyOnSamePosition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.UniqueTokenFilter.OnlyOnSamePosition" />
      <MemberSignature Language="VB.NET" Value="Public Property OnlyOnSamePosition As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OnlyOnSamePosition : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.UniqueTokenFilter.OnlyOnSamePosition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onlyOnSamePosition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c28b3-109">Ruft ab oder legt einen Wert, der angibt, ob Duplikate nur an der gleichen Position zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="c28b3-109">Gets or sets a value indicating whether to remove duplicates only at the same position.</span></span> <span data-ttu-id="c28b3-110">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="c28b3-110">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.UniqueTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="uniqueTokenFilter.Validate " />
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
            <span data-ttu-id="c28b3-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c28b3-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c28b3-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c28b3-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>