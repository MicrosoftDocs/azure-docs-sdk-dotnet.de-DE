<Type Name="DynamicsSink" FullName="Microsoft.Azure.Management.DataFactory.Models.DynamicsSink">
  <TypeSignature Language="C#" Value="public class DynamicsSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi DynamicsSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DynamicsSink" />
  <TypeSignature Language="VB.NET" Value="Public Class DynamicsSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type DynamicsSink = class&#xA;    inherit CopySink" />
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
            <span data-ttu-id="09e69-101">Eine Kopie sink Aktivität Dynamics.</span><span class="sxs-lookup"><span data-stu-id="09e69-101">A copy activity Dynamics sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicsSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09e69-102">Initialisiert eine neue Instanz der DynamicsSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09e69-102">Initializes a new instance of the DynamicsSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicsSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object ignoreNullValues = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object ignoreNullValues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional ignoreNullValues As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DynamicsSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DynamicsSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.DynamicsSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, ignoreNullValues)" />
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
        <Parameter Name="ignoreNullValues" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="09e69-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="09e69-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="09e69-104">Schreiben Sie die Batchgröße.</span><span class="sxs-lookup"><span data-stu-id="09e69-104">Write batch size.</span></span> <span data-ttu-id="09e69-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="09e69-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="09e69-106">BatchTimeout zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="09e69-106">Write batch timeout.</span></span> <span data-ttu-id="09e69-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="09e69-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="09e69-108">Sink Wiederholungsanzahl.</span><span class="sxs-lookup"><span data-stu-id="09e69-108">Sink retry count.</span></span> <span data-ttu-id="09e69-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="09e69-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="09e69-110">Sink Wiederholung warten.</span><span class="sxs-lookup"><span data-stu-id="09e69-110">Sink retry wait.</span></span> <span data-ttu-id="09e69-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="09e69-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="ignoreNullValues"><span data-ttu-id="09e69-112">Ignoriert das Flag, der angibt, gibt an, ob null-Werte aus dem Eingabedataset (außer Schlüsselfelder) während des Schreibvorgangs.</span><span class="sxs-lookup"><span data-stu-id="09e69-112">The flag indicating whether ignore null values from input dataset (except key fields) during write operation.</span></span> <span data-ttu-id="09e69-113">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="09e69-113">Default is false.</span></span> <span data-ttu-id="09e69-114">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="09e69-114">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="09e69-115">Initialisiert eine neue Instanz der DynamicsSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09e69-115">Initializes a new instance of the DynamicsSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreNullValues">
      <MemberSignature Language="C#" Value="public object IgnoreNullValues { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object IgnoreNullValues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsSink.IgnoreNullValues" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreNullValues As Object" />
      <MemberSignature Language="F#" Value="member this.IgnoreNullValues : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsSink.IgnoreNullValues" />
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
            <span data-ttu-id="09e69-116">Ruft ab oder legt das Flag, der angibt, gibt an, ob ignorieren null-Werte aus dem Eingabedataset (außer Schlüsselfelder) während der Schreibvorgang.</span><span class="sxs-lookup"><span data-stu-id="09e69-116">Gets or sets the flag indicating whether ignore null values from input dataset (except key fields) during write operation.</span></span> <span data-ttu-id="09e69-117">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="09e69-117">Default is false.</span></span> <span data-ttu-id="09e69-118">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="09e69-118">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteBehavior">
      <MemberSignature Language="C#" Value="public static string WriteBehavior { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string WriteBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsSink.WriteBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property WriteBehavior As String" />
      <MemberSignature Language="F#" Value="member this.WriteBehavior : string" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsSink.WriteBehavior" />
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
            <span data-ttu-id="09e69-119">Das Schreibverhalten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="09e69-119">The write behavior for the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>