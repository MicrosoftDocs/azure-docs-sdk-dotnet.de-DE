<Type Name="UriQueryBuilder" FullName="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder">
  <TypeSignature Language="C#" Value="public class UriQueryBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UriQueryBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class UriQueryBuilder" />
  <TypeSignature Language="F#" Value="type UriQueryBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0c2ec-101">Eine benutzerfreundliche-Klasse zum Erstellen von Abfragezeichenfolgen URI.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-101">A convenience class for constructing URI query strings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UriQueryBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0c2ec-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UriQueryBuilder (Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.#ctor(Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (builder As UriQueryBuilder)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder : Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder -&gt; Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" Usage="new Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
      </Parameters>
      <Docs>
        <param name="builder"><span data-ttu-id="0c2ec-103">Das <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />, dessen Elemente in das neue <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-103">The <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> whose elements are copied to the new <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />.</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Klasse, die Elemente enthält, die aus dem angegebenen kopierte <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> class that contains elements copied from the specified <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public virtual void Add (string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Add(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Add (name As String, value As String)" />
      <MemberSignature Language="F#" Value="abstract member Add : string * string -&gt; unit&#xA;override this.Add : string * string -&gt; unit" Usage="uriQueryBuilder.Add (name, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0c2ec-105">Der Zeichenfolgenname der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-105">The query string name.</span></span></param>
        <param name="value"><span data-ttu-id="0c2ec-106">Der Wert der Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-106">The query string value.</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-107">Fügen Sie den Wert der Abfragezeichenfolge mit URI Escapezeichen hinzu.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-107">Add the query string value with URI escaping.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRange">
      <MemberSignature Language="C#" Value="public void AddRange (System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,string&gt;&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRange(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, string&gt;&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddRange(System.Collections.Generic.IEnumerable{System.Collections.Generic.KeyValuePair{System.String,System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddRange (parameters As IEnumerable(Of KeyValuePair(Of String, String)))" />
      <MemberSignature Language="F#" Value="member this.AddRange : seq&lt;System.Collections.Generic.KeyValuePair&lt;string, string&gt;&gt; -&gt; unit" Usage="uriQueryBuilder.AddRange parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="0c2ec-108">Der Satz von Name/Wert-Paare von Abfrage Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="0c2ec-108">The set of query string name/value pairs</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-109">Fügen Sie mehrere Abfragezeichenfolgen-Werte mit Escapezeichen URI hinzu.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-109">Add multiple query string values with URI escaping.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri AddToUri (Microsoft.WindowsAzure.Storage.StorageUri storageUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.StorageUri AddToUri(class Microsoft.WindowsAzure.Storage.StorageUri storageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddToUri(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="F#" Value="member this.AddToUri : Microsoft.WindowsAzure.Storage.StorageUri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="uriQueryBuilder.AddToUri storageUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="storageUri"><span data-ttu-id="0c2ec-110">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> mit dem ursprünglichen URI an, einschließlich aller vorhandenen Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-110">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> containing the original URI, including any existing query parameters.</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-111">Fügt einen Abfrageparameter an einen URI an.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-111">Adds a query parameter to a URI.</span></span>
            </summary>
        <returns><span data-ttu-id="0c2ec-112">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt mit dem neuen Abfrageparameter angefügt.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-112">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> object with the new query parameter appended.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUri">
      <MemberSignature Language="C#" Value="public virtual Uri AddToUri (Uri uri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Uri AddToUri(class System.Uri uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddToUri(System.Uri)" />
      <MemberSignature Language="F#" Value="abstract member AddToUri : Uri -&gt; Uri&#xA;override this.AddToUri : Uri -&gt; Uri" Usage="uriQueryBuilder.AddToUri uri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="0c2ec-113">Ein <see cref="T:System.Uri" /> Objekt, das den ursprünglichen URI einschließlich vorhandene Abfrageparameter enthält.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-113">A <see cref="T:System.Uri" /> object containing the original URI, including any existing query parameters.</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-114">Fügt einen Abfrageparameter an einen URI an.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-114">Adds a query parameter to a URI.</span></span>
            </summary>
        <returns><span data-ttu-id="0c2ec-115">Ein <see cref="T:System.Uri" /> Objekt mit dem neuen Abfrageparameter angefügt.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-115">A <see cref="T:System.Uri" /> object with the new query parameter appended.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUriCore">
      <MemberSignature Language="C#" Value="protected Uri AddToUriCore (Uri uri);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Uri AddToUriCore(class System.Uri uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddToUriCore(System.Uri)" />
      <MemberSignature Language="F#" Value="member this.AddToUriCore : Uri -&gt; Uri" Usage="uriQueryBuilder.AddToUriCore uri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="0c2ec-116">Ein <see cref="T:System.Uri" /> Objekt, das den ursprünglichen URI einschließlich vorhandene Abfrageparameter enthält.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-116">A <see cref="T:System.Uri" /> object containing the original URI, including any existing query parameters.</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-117">Fügt einen Abfrageparameter an einen URI an.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-117">Adds a query parameter to a URI.</span></span>
            </summary>
        <returns><span data-ttu-id="0c2ec-118">Ein <see cref="T:System.Uri" /> Objekt mit dem neuen Abfrageparameter angefügt.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-118">A <see cref="T:System.Uri" /> object with the new query parameter appended.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsQueryStringName">
      <MemberSignature Language="C#" Value="public bool ContainsQueryStringName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool ContainsQueryStringName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.ContainsQueryStringName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsQueryStringName (name As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.ContainsQueryStringName : string -&gt; bool" Usage="uriQueryBuilder.ContainsQueryStringName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0c2ec-119">Der Zeichenfolgenname der Abfrage</span><span class="sxs-lookup"><span data-stu-id="0c2ec-119">The query string name</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-120">Bestimmt, ob der Name der Abfrage-Zeichenfolge in der Abfragezeichenfolge vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-120">Determines whether the query string name exists in the query string.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public string this[string name] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(name As String) As String" />
      <MemberSignature Language="F#" Value="member this.Item(string) : string" Usage="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0c2ec-121">Der Zeichenfolgenname der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-121">The query string name.</span></span></param>
        <summary>
            <span data-ttu-id="0c2ec-122">Ruft den Wert der Abfragezeichenfolge verknüpft sind, mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-122">Gets the query string value associated with the given name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Parameters" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c2ec-123">Speichert die Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-123">Stores the query parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="uriQueryBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0c2ec-124">Gibt eine <see cref="T:System.String" /> mit dem URI.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-124">Returns a <see cref="T:System.String" /> containing the URI.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0c2ec-125">Ein <see cref="T:System.String" /> , das den URI enthält.</span><span class="sxs-lookup"><span data-stu-id="0c2ec-125">A <see cref="T:System.String" /> containing the URI.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>