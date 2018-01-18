<Type Name="SavedSearch" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch">
  <TypeSignature Language="C#" Value="public class SavedSearch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SavedSearch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" />
  <TypeSignature Language="VB.NET" Value="Public Class SavedSearch" />
  <TypeSignature Language="F#" Value="type SavedSearch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="55a62-101">Das Wertobjekt für gespeicherte Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="55a62-101">Value object for saved search results.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SavedSearch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55a62-102">Initialisiert eine neue Instanz der Klasse SavedSearch.</span><span class="sxs-lookup"><span data-stu-id="55a62-102">Initializes a new instance of the SavedSearch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SavedSearch (string category, string displayName, string query, long version, string id = null, string etag = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string category, string displayName, string query, int64 version, string id, string etag, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.#ctor(System.String,System.String,System.String,System.Int64,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.OperationalInsights.Models.Tag})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As String, displayName As String, query As String, version As Long, Optional id As String = null, Optional etag As String = null, Optional tags As IList(Of Tag) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch : string * string * string * int64 * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch (category, displayName, query, version, id, etag, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt;" />
      </Parameters>
      <Docs>
        <param name="category"><span data-ttu-id="55a62-103">Die Kategorie der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="55a62-103">The category of the saved search.</span></span> <span data-ttu-id="55a62-104">Dadurch wird den Benutzer eine gespeicherte Suche schneller finden.</span><span class="sxs-lookup"><span data-stu-id="55a62-104">This helps the user to find a saved search faster.</span></span> </param>
        <param name="displayName"><span data-ttu-id="55a62-105">Name der gespeicherten Suche angezeigt.</span><span class="sxs-lookup"><span data-stu-id="55a62-105">Saved search display name.</span></span></param>
        <param name="query"><span data-ttu-id="55a62-106">Der Abfrageausdruck für den gespeicherten Suchvorgang.</span><span class="sxs-lookup"><span data-stu-id="55a62-106">The query expression for the saved search.</span></span>
            <span data-ttu-id="55a62-107">Finden Sie unter https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference Referenz.</span><span class="sxs-lookup"><span data-stu-id="55a62-107">Please see https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference for reference.</span></span></param>
        <param name="version"><span data-ttu-id="55a62-108">Die Versionsnummer von der Abfrage gehandhabt.</span><span class="sxs-lookup"><span data-stu-id="55a62-108">The version number of the query lanuage.</span></span> <span data-ttu-id="55a62-109">Nur Version 1 wird hier zulässig.</span><span class="sxs-lookup"><span data-stu-id="55a62-109">Only verion 1 is allowed here.</span></span></param>
        <param name="id"><span data-ttu-id="55a62-110">Die Id der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="55a62-110">The id of the saved search.</span></span></param>
        <param name="etag"><span data-ttu-id="55a62-111">Das Etag der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="55a62-111">The etag of the saved search.</span></span></param>
        <param name="tags"><span data-ttu-id="55a62-112">Der RFID-Transponder an den gespeicherten Suchvorgang angefügt.</span><span class="sxs-lookup"><span data-stu-id="55a62-112">The tags attached to the saved search.</span></span></param>
        <summary>
            <span data-ttu-id="55a62-113">Initialisiert eine neue Instanz der Klasse SavedSearch.</span><span class="sxs-lookup"><span data-stu-id="55a62-113">Initializes a new instance of the SavedSearch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-114">Ruft ab oder legt die Kategorie der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="55a62-114">Gets or sets the category of the saved search.</span></span> <span data-ttu-id="55a62-115">Dadurch wird den Benutzer eine gespeicherte Suche schneller finden.</span><span class="sxs-lookup"><span data-stu-id="55a62-115">This helps the user to find a saved search faster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.DisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-116">Ruft ab oder legt ihn fest, die gespeicherte Suche Anzeigename.</span><span class="sxs-lookup"><span data-stu-id="55a62-116">Gets or sets saved search display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-117">Ruft ab oder legt das Etag der gespeicherten Suche fest.</span><span class="sxs-lookup"><span data-stu-id="55a62-117">Gets or sets the etag of the saved search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-118">Ruft die Id der gespeicherten Suche an.</span><span class="sxs-lookup"><span data-stu-id="55a62-118">Gets the id of the saved search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-119">Abrufen oder Festlegen der Abfrageausdruck für den gespeicherten Suchvorgang.</span><span class="sxs-lookup"><span data-stu-id="55a62-119">Gets or sets the query expression for the saved search.</span></span> <span data-ttu-id="55a62-120">Finden Sie unter https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference Referenz.</span><span class="sxs-lookup"><span data-stu-id="55a62-120">Please see https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference for reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of Tag)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-121">Abrufen oder Festlegen der RFID-Transponder an den gespeicherten Suchvorgang angefügt.</span><span class="sxs-lookup"><span data-stu-id="55a62-121">Gets or sets the tags attached to the saved search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="savedSearch.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55a62-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="55a62-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="55a62-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="55a62-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public long Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Long" />
      <MemberSignature Language="F#" Value="member this.Version : int64 with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55a62-124">Ruft ab oder legt die Anzahl von der Abfrage gehandhabt.</span><span class="sxs-lookup"><span data-stu-id="55a62-124">Gets or sets the version number of the query lanuage.</span></span> <span data-ttu-id="55a62-125">Nur Version 1 wird hier zulässig.</span><span class="sxs-lookup"><span data-stu-id="55a62-125">Only verion 1 is allowed here.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>