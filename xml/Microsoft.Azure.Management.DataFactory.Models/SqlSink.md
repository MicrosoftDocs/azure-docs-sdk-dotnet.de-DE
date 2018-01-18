<Type Name="SqlSink" FullName="Microsoft.Azure.Management.DataFactory.Models.SqlSink">
  <TypeSignature Language="C#" Value="public class SqlSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SqlSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SqlSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc306-101">Eine SQL-Senke kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="dc306-101">A copy activity SQL sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlSink.#ctor" />
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
            <span data-ttu-id="dc306-102">Initialisiert eine neue Instanz der SqlSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc306-102">Initializes a new instance of the SqlSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object sqlWriterStoredProcedureName = null, object sqlWriterTableType = null, object preCopyScript = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object sqlWriterStoredProcedureName, object sqlWriterTableType, object preCopyScript, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional sqlWriterStoredProcedureName As Object = null, Optional sqlWriterTableType As Object = null, Optional preCopyScript As Object = null, Optional storedProcedureParameters As IDictionary(Of String, StoredProcedureParameter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SqlSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.SqlSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.SqlSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, sqlWriterStoredProcedureName, sqlWriterTableType, preCopyScript, storedProcedureParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="writeBatchSize" Type="System.Object" />
        <Parameter Name="writeBatchTimeout" Type="System.Object" />
        <Parameter Name="sinkRetryCount" Type="System.Object" />
        <Parameter Name="sinkRetryWait" Type="System.Object" />
        <Parameter Name="sqlWriterStoredProcedureName" Type="System.Object" />
        <Parameter Name="sqlWriterTableType" Type="System.Object" />
        <Parameter Name="preCopyScript" Type="System.Object" />
        <Parameter Name="storedProcedureParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="dc306-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="dc306-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="dc306-104">Schreiben Sie die Batchgröße.</span><span class="sxs-lookup"><span data-stu-id="dc306-104">Write batch size.</span></span> <span data-ttu-id="dc306-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="dc306-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="dc306-106">BatchTimeout zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="dc306-106">Write batch timeout.</span></span> <span data-ttu-id="dc306-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="dc306-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="dc306-108">Sink Wiederholungsanzahl.</span><span class="sxs-lookup"><span data-stu-id="dc306-108">Sink retry count.</span></span> <span data-ttu-id="dc306-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="dc306-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="dc306-110">Sink Wiederholung warten.</span><span class="sxs-lookup"><span data-stu-id="dc306-110">Sink retry wait.</span></span> <span data-ttu-id="dc306-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="dc306-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sqlWriterStoredProcedureName"><span data-ttu-id="dc306-112">Name der SQL Writer-gespeicherte Prozedur.</span><span class="sxs-lookup"><span data-stu-id="dc306-112">SQL writer stored procedure name.</span></span> <span data-ttu-id="dc306-113">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="dc306-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="sqlWriterTableType"><span data-ttu-id="dc306-114">SQL Writer-Tabellentyp.</span><span class="sxs-lookup"><span data-stu-id="dc306-114">SQL writer table type.</span></span> <span data-ttu-id="dc306-115">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="dc306-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="preCopyScript"><span data-ttu-id="dc306-116">Vor dem Kopieren der SQL-Skript.</span><span class="sxs-lookup"><span data-stu-id="dc306-116">SQL pre-copy script.</span></span> <span data-ttu-id="dc306-117">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="dc306-117">Type: string (or Expression with resultType string).</span></span></param>
        <param name="storedProcedureParameters"><span data-ttu-id="dc306-118">SQL Parameter der gespeicherten Prozeduren.</span><span class="sxs-lookup"><span data-stu-id="dc306-118">SQL stored procedure parameters.</span></span></param>
        <summary>
            <span data-ttu-id="dc306-119">Initialisiert eine neue Instanz der SqlSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc306-119">Initializes a new instance of the SqlSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreCopyScript">
      <MemberSignature Language="C#" Value="public object PreCopyScript { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PreCopyScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSink.PreCopyScript" />
      <MemberSignature Language="VB.NET" Value="Public Property PreCopyScript As Object" />
      <MemberSignature Language="F#" Value="member this.PreCopyScript : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSink.PreCopyScript" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preCopyScript")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc306-120">Ruft ab, oder legt ihn fest SQL vor dem Kopieren-Skript.</span><span class="sxs-lookup"><span data-stu-id="dc306-120">Gets or sets SQL pre-copy script.</span></span> <span data-ttu-id="dc306-121">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="dc306-121">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlWriterStoredProcedureName">
      <MemberSignature Language="C#" Value="public object SqlWriterStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlWriterStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSink.SqlWriterStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlWriterStoredProcedureName As Object" />
      <MemberSignature Language="F#" Value="member this.SqlWriterStoredProcedureName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSink.SqlWriterStoredProcedureName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlWriterStoredProcedureName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc306-122">Ruft ab, oder legt ihn fest Name für die gespeicherte Prozedur von SQL Writer.</span><span class="sxs-lookup"><span data-stu-id="dc306-122">Gets or sets SQL writer stored procedure name.</span></span> <span data-ttu-id="dc306-123">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="dc306-123">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlWriterTableType">
      <MemberSignature Language="C#" Value="public object SqlWriterTableType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlWriterTableType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSink.SqlWriterTableType" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlWriterTableType As Object" />
      <MemberSignature Language="F#" Value="member this.SqlWriterTableType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSink.SqlWriterTableType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlWriterTableType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc306-124">Abrufen oder Festlegen der SQL Writer-Tabellentyp.</span><span class="sxs-lookup"><span data-stu-id="dc306-124">Gets or sets SQL writer table type.</span></span> <span data-ttu-id="dc306-125">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="dc306-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSink.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, StoredProcedureParameter)" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSink.StoredProcedureParameters" />
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
            <span data-ttu-id="dc306-126">Abrufen oder Festlegen der Parameter der gespeicherten SQL-Prozeduren.</span><span class="sxs-lookup"><span data-stu-id="dc306-126">Gets or sets SQL stored procedure parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>