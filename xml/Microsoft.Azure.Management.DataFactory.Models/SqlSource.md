<Type Name="SqlSource" FullName="Microsoft.Azure.Management.DataFactory.Models.SqlSource">
  <TypeSignature Language="C#" Value="public class SqlSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SqlSource" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type SqlSource = class&#xA;    inherit CopySource" />
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
            <span data-ttu-id="63e7b-101">Eine SQL-Datenquelle kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="63e7b-101">A copy activity SQL source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlSource.#ctor" />
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
            <span data-ttu-id="63e7b-102">Initialisiert eine neue Instanz der SqlSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63e7b-102">Initializes a new instance of the SqlSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object sqlReaderQuery = null, object sqlReaderStoredProcedureName = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object sqlReaderQuery, object sqlReaderStoredProcedureName, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional sqlReaderQuery As Object = null, Optional sqlReaderStoredProcedureName As Object = null, Optional storedProcedureParameters As IDictionary(Of String, StoredProcedureParameter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SqlSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.SqlSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.SqlSource (additionalProperties, sourceRetryCount, sourceRetryWait, sqlReaderQuery, sqlReaderStoredProcedureName, storedProcedureParameters)" />
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
        <Parameter Name="storedProcedureParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="63e7b-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="63e7b-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="63e7b-104">Anzahl von Wiederholungsversuchen Quelle.</span><span class="sxs-lookup"><span data-stu-id="63e7b-104">Source retry count.</span></span> <span data-ttu-id="63e7b-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="63e7b-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="63e7b-106">Warten Sie Quelle, versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="63e7b-106">Source retry wait.</span></span> <span data-ttu-id="63e7b-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="63e7b-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sqlReaderQuery"><span data-ttu-id="63e7b-108">SQL-Abfrage-Reader.</span><span class="sxs-lookup"><span data-stu-id="63e7b-108">SQL reader query.</span></span> <span data-ttu-id="63e7b-109">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="63e7b-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="sqlReaderStoredProcedureName"><span data-ttu-id="63e7b-110">Der Name der gespeicherten Prozedur für eine SQL-Datenbank-Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="63e7b-110">Name of the stored procedure for a SQL Database source.</span></span> <span data-ttu-id="63e7b-111">Dies kann nicht gleichzeitig als die SqlReaderQuery verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="63e7b-111">This cannot be used at the same time as SqlReaderQuery.</span></span> <span data-ttu-id="63e7b-112">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="63e7b-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="storedProcedureParameters"><span data-ttu-id="63e7b-113">Wert und Typ für Parameter gespeicherter Prozeduren festlegen.</span><span class="sxs-lookup"><span data-stu-id="63e7b-113">Value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="63e7b-114">Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".</span><span class="sxs-lookup"><span data-stu-id="63e7b-114">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span></param>
        <summary>
            <span data-ttu-id="63e7b-115">Initialisiert eine neue Instanz der SqlSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63e7b-115">Initializes a new instance of the SqlSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderQuery">
      <MemberSignature Language="C#" Value="public object SqlReaderQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlReaderQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderQuery As Object" />
      <MemberSignature Language="F#" Value="member this.SqlReaderQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderQuery" />
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
            <span data-ttu-id="63e7b-116">Ruft ab, oder legt ihn fest SQL Reader-Abfrage.</span><span class="sxs-lookup"><span data-stu-id="63e7b-116">Gets or sets SQL reader query.</span></span> <span data-ttu-id="63e7b-117">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="63e7b-117">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderStoredProcedureName">
      <MemberSignature Language="C#" Value="public object SqlReaderStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlReaderStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderStoredProcedureName As Object" />
      <MemberSignature Language="F#" Value="member this.SqlReaderStoredProcedureName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderStoredProcedureName" />
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
            <span data-ttu-id="63e7b-118">Ruft ab oder legt den Namen der gespeicherten Prozedur für eine SQL-Datenbank-Datenquelle fest.</span><span class="sxs-lookup"><span data-stu-id="63e7b-118">Gets or sets name of the stored procedure for a SQL Database source.</span></span> <span data-ttu-id="63e7b-119">Dies kann nicht gleichzeitig als die SqlReaderQuery verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="63e7b-119">This cannot be used at the same time as SqlReaderQuery.</span></span>
            <span data-ttu-id="63e7b-120">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="63e7b-120">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSource.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, StoredProcedureParameter)" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSource.StoredProcedureParameters" />
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
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63e7b-121">Ruft ab, oder legt sie fest, Wert und Typ für Parameter gespeicherter Prozeduren festlegen.</span><span class="sxs-lookup"><span data-stu-id="63e7b-121">Gets or sets value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="63e7b-122">Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".</span><span class="sxs-lookup"><span data-stu-id="63e7b-122">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>