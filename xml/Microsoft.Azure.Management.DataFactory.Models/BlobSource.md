<Type Name="BlobSource" FullName="Microsoft.Azure.Management.DataFactory.Models.BlobSource">
  <TypeSignature Language="C#" Value="public class BlobSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.BlobSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type BlobSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="73b9d-101">Ein Azure-Blob-Quelle kopieren Aktivität.</span><span class="sxs-lookup"><span data-stu-id="73b9d-101">A copy activity Azure Blob source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73b9d-102">Initialisiert eine neue Instanz der BlobSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73b9d-102">Initializes a new instance of the BlobSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object treatEmptyAsNull = null, object skipHeaderLineCount = null, object recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object treatEmptyAsNull, object skipHeaderLineCount, object recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional treatEmptyAsNull As Object = null, Optional skipHeaderLineCount As Object = null, Optional recursive As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.BlobSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.BlobSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.BlobSource (additionalProperties, sourceRetryCount, sourceRetryWait, treatEmptyAsNull, skipHeaderLineCount, recursive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="treatEmptyAsNull" Type="System.Object" />
        <Parameter Name="skipHeaderLineCount" Type="System.Object" />
        <Parameter Name="recursive" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="73b9d-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="73b9d-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="73b9d-104">Anzahl von Wiederholungsversuchen Quelle.</span><span class="sxs-lookup"><span data-stu-id="73b9d-104">Source retry count.</span></span> <span data-ttu-id="73b9d-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="73b9d-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="73b9d-106">Warten Sie Quelle, versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="73b9d-106">Source retry wait.</span></span> <span data-ttu-id="73b9d-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="73b9d-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="treatEmptyAsNull"><span data-ttu-id="73b9d-108">Behandeln Sie als null, leer.</span><span class="sxs-lookup"><span data-stu-id="73b9d-108">Treat empty as null.</span></span> <span data-ttu-id="73b9d-109">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="73b9d-109">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="skipHeaderLineCount"><span data-ttu-id="73b9d-110">Anzahl der Kopfzeilen aus jedes Blob zu überspringen.</span><span class="sxs-lookup"><span data-stu-id="73b9d-110">Number of header lines to skip from each blob.</span></span> <span data-ttu-id="73b9d-111">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="73b9d-111">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="recursive"><span data-ttu-id="73b9d-112">Bei "true", werden Dateien unter dem Ordnerpfad rekursiv gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="73b9d-112">If true, files under the folder path will be read recursively.</span></span> <span data-ttu-id="73b9d-113">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="73b9d-113">Default is true.</span></span> <span data-ttu-id="73b9d-114">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="73b9d-114">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="73b9d-115">Initialisiert eine neue Instanz der BlobSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73b9d-115">Initializes a new instance of the BlobSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public object Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Object" />
      <MemberSignature Language="F#" Value="member this.Recursive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSource.Recursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73b9d-116">Ruft ab oder legt fest, ob "true" werden Dateien unter dem Ordnerpfad rekursiv gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="73b9d-116">Gets or sets if true, files under the folder path will be read recursively.</span></span> <span data-ttu-id="73b9d-117">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="73b9d-117">Default is true.</span></span> <span data-ttu-id="73b9d-118">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="73b9d-118">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipHeaderLineCount">
      <MemberSignature Language="C#" Value="public object SkipHeaderLineCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SkipHeaderLineCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSource.SkipHeaderLineCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipHeaderLineCount As Object" />
      <MemberSignature Language="F#" Value="member this.SkipHeaderLineCount : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSource.SkipHeaderLineCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skipHeaderLineCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73b9d-119">Ruft ab oder legt die Anzahl der Kopfzeilen aus jedes Blob zu überspringen.</span><span class="sxs-lookup"><span data-stu-id="73b9d-119">Gets or sets number of header lines to skip from each blob.</span></span> <span data-ttu-id="73b9d-120">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="73b9d-120">Type: integer (or Expression with resultType integer).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TreatEmptyAsNull">
      <MemberSignature Language="C#" Value="public object TreatEmptyAsNull { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TreatEmptyAsNull" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSource.TreatEmptyAsNull" />
      <MemberSignature Language="VB.NET" Value="Public Property TreatEmptyAsNull As Object" />
      <MemberSignature Language="F#" Value="member this.TreatEmptyAsNull : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSource.TreatEmptyAsNull" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="treatEmptyAsNull")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73b9d-121">Ruft ab oder legt behandeln leere als null.</span><span class="sxs-lookup"><span data-stu-id="73b9d-121">Gets or sets treat empty as null.</span></span> <span data-ttu-id="73b9d-122">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="73b9d-122">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>