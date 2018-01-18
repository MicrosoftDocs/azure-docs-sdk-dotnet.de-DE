<Type Name="SqlDWSource" FullName="Microsoft.Azure.Management.DataFactory.Models.SqlDWSource">
  <TypeSignature Language="C#" Value="public class SqlDWSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlDWSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SqlDWSource" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlDWSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type SqlDWSource = class&#xA;    inherit CopySource" />
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
            <span data-ttu-id="0aa06-101">Eine SQL Data Warehouse-Quelle kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="0aa06-101">A copy activity SQL Data Warehouse source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlDWSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.#ctor" />
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
            <span data-ttu-id="0aa06-102">Initialisiert eine neue Instanz der SqlDWSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0aa06-102">Initializes a new instance of the SqlDWSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlDWSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object sqlReaderQuery = null, object sqlReaderStoredProcedureName = null, object storedProcedureParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object sqlReaderQuery, object sqlReaderStoredProcedureName, object storedProcedureParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional sqlReaderQuery As Object = null, Optional sqlReaderStoredProcedureName As Object = null, Optional storedProcedureParameters As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SqlDWSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SqlDWSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.SqlDWSource (additionalProperties, sourceRetryCount, sourceRetryWait, sqlReaderQuery, sqlReaderStoredProcedureName, storedProcedureParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="sqlReaderQuery" Type="System.Object" />
        <Parameter Name="sqlReaderStoredProcedureName" Type="System.Object" />
        <Parameter Name="storedProcedureParameters" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="0aa06-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="0aa06-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="0aa06-104">Anzahl von Wiederholungsversuchen Quelle.</span><span class="sxs-lookup"><span data-stu-id="0aa06-104">Source retry count.</span></span> <span data-ttu-id="0aa06-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="0aa06-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="0aa06-106">Warten Sie Quelle, versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="0aa06-106">Source retry wait.</span></span> <span data-ttu-id="0aa06-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="0aa06-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sqlReaderQuery"><span data-ttu-id="0aa06-108">SQL Data Warehouse-Reader-Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0aa06-108">SQL Data Warehouse reader query.</span></span> <span data-ttu-id="0aa06-109">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="0aa06-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="sqlReaderStoredProcedureName"><span data-ttu-id="0aa06-110">Der Name der gespeicherten Prozedur für eine SQL Data Warehouse-Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="0aa06-110">Name of the stored procedure for a SQL Data Warehouse source.</span></span> <span data-ttu-id="0aa06-111">Dies kann nicht gleichzeitig als die SqlReaderQuery verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0aa06-111">This cannot be used at the same time as SqlReaderQuery.</span></span> <span data-ttu-id="0aa06-112">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="0aa06-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="storedProcedureParameters"><span data-ttu-id="0aa06-113">Wert und Typ für Parameter gespeicherter Prozeduren festlegen.</span><span class="sxs-lookup"><span data-stu-id="0aa06-113">Value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="0aa06-114">Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".</span><span class="sxs-lookup"><span data-stu-id="0aa06-114">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span> <span data-ttu-id="0aa06-115">Typ: Objekt (oder Ausdruck mit ResultType-Objekt), ItemType: StoredProcedureParameter.</span><span class="sxs-lookup"><span data-stu-id="0aa06-115">Type: object (or Expression with resultType object), itemType: StoredProcedureParameter.</span></span></param>
        <summary>
            <span data-ttu-id="0aa06-116">Initialisiert eine neue Instanz der SqlDWSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0aa06-116">Initializes a new instance of the SqlDWSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderQuery">
      <MemberSignature Language="C#" Value="public object SqlReaderQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlReaderQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.SqlReaderQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderQuery As Object" />
      <MemberSignature Language="F#" Value="member this.SqlReaderQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.SqlReaderQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlReaderQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0aa06-117">Ruft ab, oder legt ihn fest SQL Data Warehouse-Reader-Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0aa06-117">Gets or sets SQL Data Warehouse reader query.</span></span> <span data-ttu-id="0aa06-118">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="0aa06-118">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderStoredProcedureName">
      <MemberSignature Language="C#" Value="public object SqlReaderStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlReaderStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.SqlReaderStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderStoredProcedureName As Object" />
      <MemberSignature Language="F#" Value="member this.SqlReaderStoredProcedureName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.SqlReaderStoredProcedureName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlReaderStoredProcedureName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0aa06-119">Ruft ab oder legt den Namen der gespeicherten Prozedur für eine SQL Data Warehouse-Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="0aa06-119">Gets or sets name of the stored procedure for a SQL Data Warehouse source.</span></span> <span data-ttu-id="0aa06-120">Dies kann nicht gleichzeitig als die SqlReaderQuery verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0aa06-120">This cannot be used at the same time as SqlReaderQuery.</span></span>
            <span data-ttu-id="0aa06-121">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="0aa06-121">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public object StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As Object" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlDWSource.StoredProcedureParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storedProcedureParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0aa06-122">Ruft ab, oder legt sie fest, Wert und Typ für Parameter gespeicherter Prozeduren festlegen.</span><span class="sxs-lookup"><span data-stu-id="0aa06-122">Gets or sets value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="0aa06-123">Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".</span><span class="sxs-lookup"><span data-stu-id="0aa06-123">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span>
            <span data-ttu-id="0aa06-124">Typ: Objekt (oder Ausdruck mit ResultType-Objekt), ItemType: StoredProcedureParameter.</span><span class="sxs-lookup"><span data-stu-id="0aa06-124">Type: object (or Expression with resultType object), itemType: StoredProcedureParameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>