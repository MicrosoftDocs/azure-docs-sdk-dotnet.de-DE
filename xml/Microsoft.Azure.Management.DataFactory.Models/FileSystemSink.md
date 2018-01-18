<Type Name="FileSystemSink" FullName="Microsoft.Azure.Management.DataFactory.Models.FileSystemSink">
  <TypeSignature Language="C#" Value="public class FileSystemSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileSystemSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.FileSystemSink" />
  <TypeSignature Language="VB.NET" Value="Public Class FileSystemSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type FileSystemSink = class&#xA;    inherit CopySink" />
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
            <span data-ttu-id="5bb29-101">Kopieren-Aktivität Datei System Senke.</span><span class="sxs-lookup"><span data-stu-id="5bb29-101">A copy activity file system sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileSystemSink.#ctor" />
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
            <span data-ttu-id="5bb29-102">Initialisiert eine neue Instanz der FileSystemSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5bb29-102">Initializes a new instance of the FileSystemSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, string copyBehavior = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, string copyBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileSystemSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional copyBehavior As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.FileSystemSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.FileSystemSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.FileSystemSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, copyBehavior)" />
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
        <Parameter Name="copyBehavior" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="5bb29-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="5bb29-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="5bb29-104">Schreiben Sie die Batchgröße.</span><span class="sxs-lookup"><span data-stu-id="5bb29-104">Write batch size.</span></span> <span data-ttu-id="5bb29-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="5bb29-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="5bb29-106">BatchTimeout zu schreiben.</span><span class="sxs-lookup"><span data-stu-id="5bb29-106">Write batch timeout.</span></span> <span data-ttu-id="5bb29-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="5bb29-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="5bb29-108">Sink Wiederholungsanzahl.</span><span class="sxs-lookup"><span data-stu-id="5bb29-108">Sink retry count.</span></span> <span data-ttu-id="5bb29-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="5bb29-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="5bb29-110">Sink Wiederholung warten.</span><span class="sxs-lookup"><span data-stu-id="5bb29-110">Sink retry wait.</span></span> <span data-ttu-id="5bb29-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="5bb29-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="copyBehavior"><span data-ttu-id="5bb29-112">Der Typ der Kopierverhalten für die Kopie Senke.</span><span class="sxs-lookup"><span data-stu-id="5bb29-112">The type of copy behavior for copy sink.</span></span>
            <span data-ttu-id="5bb29-113">Folgende Werte sind möglich: "PreserveHierarchy", "FlattenHierarchy", "MergeFiles"</span><span class="sxs-lookup"><span data-stu-id="5bb29-113">Possible values include: 'PreserveHierarchy', 'FlattenHierarchy', 'MergeFiles'</span></span></param>
        <summary>
            <span data-ttu-id="5bb29-114">Initialisiert eine neue Instanz der FileSystemSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5bb29-114">Initializes a new instance of the FileSystemSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyBehavior">
      <MemberSignature Language="C#" Value="public string CopyBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileSystemSink.CopyBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property CopyBehavior As String" />
      <MemberSignature Language="F#" Value="member this.CopyBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileSystemSink.CopyBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="copyBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bb29-115">Ruft ab, oder legt ihn fest Kopie Verhaltenstyp für die Kopie Senke.</span><span class="sxs-lookup"><span data-stu-id="5bb29-115">Gets or sets the type of copy behavior for copy sink.</span></span> <span data-ttu-id="5bb29-116">Folgende Werte sind möglich: "PreserveHierarchy", "FlattenHierarchy", "MergeFiles"</span><span class="sxs-lookup"><span data-stu-id="5bb29-116">Possible values include: 'PreserveHierarchy', 'FlattenHierarchy', 'MergeFiles'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>