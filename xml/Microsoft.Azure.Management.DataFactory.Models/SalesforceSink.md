<Type Name="SalesforceSink" FullName="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink">
  <TypeSignature Language="C#" Value="public class SalesforceSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SalesforceSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SalesforceSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SalesforceSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="51416-101">Eine Salesforce-Senke kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="51416-101">A copy activity Salesforce sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51416-102">Initialisiert eine neue Instanz der SalesforceSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="51416-102">Initializes a new instance of the SalesforceSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, string writeBehavior = null, object externalIdFieldName = null, object ignoreNullValues = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, string writeBehavior, object externalIdFieldName, object ignoreNullValues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.String,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional writeBehavior As String = null, Optional externalIdFieldName As Object = null, Optional ignoreNullValues As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SalesforceSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * string * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SalesforceSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.SalesforceSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, writeBehavior, externalIdFieldName, ignoreNullValues)" />
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
        <Parameter Name="writeBehavior" Type="System.String" />
        <Parameter Name="externalIdFieldName" Type="System.Object" />
        <Parameter Name="ignoreNullValues" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="51416-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="51416-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="51416-104">Schreiben Sie die Batchgröße.</span><span class="sxs-lookup"><span data-stu-id="51416-104">Write batch size.</span></span> <span data-ttu-id="51416-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="51416-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="51416-106">BatchTimeout zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="51416-106">Write batch timeout.</span></span> <span data-ttu-id="51416-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="51416-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="51416-108">Sink Wiederholungsanzahl.</span><span class="sxs-lookup"><span data-stu-id="51416-108">Sink retry count.</span></span> <span data-ttu-id="51416-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="51416-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="51416-110">Sink Wiederholung warten.</span><span class="sxs-lookup"><span data-stu-id="51416-110">Sink retry wait.</span></span> <span data-ttu-id="51416-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="51416-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="writeBehavior"><span data-ttu-id="51416-112">Das Schreibverhalten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-112">The write behavior for the operation.</span></span>
            <span data-ttu-id="51416-113">Standardmäßig ist ein Einfügevorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-113">Default is Insert.</span></span> <span data-ttu-id="51416-114">Folgende Werte sind möglich: 'Insert', "Upsert"</span><span class="sxs-lookup"><span data-stu-id="51416-114">Possible values include: 'Insert', 'Upsert'</span></span></param>
        <param name="externalIdFieldName"><span data-ttu-id="51416-115">Der Name des externen ID-Felds für den upsert-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-115">The name of the external ID field for upsert operation.</span></span> <span data-ttu-id="51416-116">Standardwert ist 'Id'-Spalte.</span><span class="sxs-lookup"><span data-stu-id="51416-116">Default value is 'Id' column.</span></span> <span data-ttu-id="51416-117">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="51416-117">Type: string (or Expression with resultType string).</span></span></param>
        <param name="ignoreNullValues"><span data-ttu-id="51416-118">Das Flag, das anzeigt, ob ignorieren null-Werte aus dem Eingabedataset (außer Schlüsselfelder) während der Schreibvorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-118">The flag indicating whether or not to ignore null values from input dataset (except key fields) during write operation.</span></span> <span data-ttu-id="51416-119">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="51416-119">Default value is false.</span></span> <span data-ttu-id="51416-120">Wenn legen Sie sie auf "true" bedeutet, dass ADF werden die Daten in das Zielobjekt beim Ausführen von Upsert/Update-Vorgang unverändert belassen und definierten Standardwert einzufügen, wenn auf diese Weise Einfügevorgang im Vergleich zu ADF der Daten in das Zielobjekt auf NULL wird beim Ausführen von Upsert aktualisieren / Vorgang zum Aktualisieren und Einfügen von NULL-Wert, bei der Insert-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-120">If set it to true, it means ADF will leave the data in the destination object unchanged when doing upsert/update operation and insert defined default value when doing insert operation, versus ADF will update the data in the destination object to NULL when doing upsert/update operation and insert NULL value when doing insert operation.</span></span> <span data-ttu-id="51416-121">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="51416-121">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="51416-122">Initialisiert eine neue Instanz der SalesforceSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="51416-122">Initializes a new instance of the SalesforceSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExternalIdFieldName">
      <MemberSignature Language="C#" Value="public object ExternalIdFieldName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ExternalIdFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.ExternalIdFieldName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExternalIdFieldName As Object" />
      <MemberSignature Language="F#" Value="member this.ExternalIdFieldName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.ExternalIdFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="externalIdFieldName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51416-123">Ruft ab oder legt den Namen des externen ID-Felds für Upsert-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-123">Gets or sets the name of the external ID field for upsert operation.</span></span> <span data-ttu-id="51416-124">Standardwert ist 'Id'-Spalte.</span><span class="sxs-lookup"><span data-stu-id="51416-124">Default value is 'Id' column.</span></span> <span data-ttu-id="51416-125">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="51416-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreNullValues">
      <MemberSignature Language="C#" Value="public object IgnoreNullValues { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object IgnoreNullValues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.IgnoreNullValues" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreNullValues As Object" />
      <MemberSignature Language="F#" Value="member this.IgnoreNullValues : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.IgnoreNullValues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreNullValues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51416-126">Ruft ab oder legt das Flag, das anzeigt, ob null-Werte aus dem Eingabedataset (außer Schlüsselfelder) beim Schreibvorgang ignoriert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="51416-126">Gets or sets the flag indicating whether or not to ignore null values from input dataset (except key fields) during write operation.</span></span> <span data-ttu-id="51416-127">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="51416-127">Default value is false.</span></span> <span data-ttu-id="51416-128">Wenn legen Sie sie auf "true" bedeutet, dass ADF werden die Daten in das Zielobjekt beim Ausführen von Upsert/Update-Vorgang unverändert belassen und definierten Standardwert einzufügen, wenn auf diese Weise Einfügevorgang im Vergleich zu ADF der Daten in das Zielobjekt auf NULL wird beim Ausführen von Upsert aktualisieren / Vorgang zum Aktualisieren und Einfügen von NULL-Wert, bei der Insert-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-128">If set it to true, it means ADF will leave the data in the destination object unchanged when doing upsert/update operation and insert defined default value when doing insert operation, versus ADF will update the data in the destination object to NULL when doing upsert/update operation and insert NULL value when doing insert operation.</span></span> <span data-ttu-id="51416-129">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="51416-129">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteBehavior">
      <MemberSignature Language="C#" Value="public string WriteBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WriteBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.WriteBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteBehavior As String" />
      <MemberSignature Language="F#" Value="member this.WriteBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceSink.WriteBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51416-130">Ruft ab oder legt das Verhalten der Schreibzugriff für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-130">Gets or sets the write behavior for the operation.</span></span> <span data-ttu-id="51416-131">Standardmäßig ist ein Einfügevorgang.</span><span class="sxs-lookup"><span data-stu-id="51416-131">Default is Insert.</span></span> <span data-ttu-id="51416-132">Folgende Werte sind möglich: 'Insert', "Upsert"</span><span class="sxs-lookup"><span data-stu-id="51416-132">Possible values include: 'Insert', 'Upsert'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>