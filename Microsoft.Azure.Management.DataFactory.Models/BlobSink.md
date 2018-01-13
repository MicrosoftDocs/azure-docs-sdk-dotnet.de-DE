<Type Name="BlobSink" FullName="Microsoft.Azure.Management.DataFactory.Models.BlobSink">
  <TypeSignature Language="C#" Value="public class BlobSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.BlobSink" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type BlobSink = class&#xA;    inherit CopySink" />
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
            Eine kopieren-Aktivität-Azure-Blob-Senke.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSink.#ctor" />
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
            Initialisiert eine neue Instanz der BlobSink-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object blobWriterOverwriteFiles = null, object blobWriterDateTimeFormat = null, object blobWriterAddHeader = null, string copyBehavior = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object blobWriterOverwriteFiles, object blobWriterDateTimeFormat, object blobWriterAddHeader, string copyBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional blobWriterOverwriteFiles As Object = null, Optional blobWriterDateTimeFormat As Object = null, Optional blobWriterAddHeader As Object = null, Optional copyBehavior As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.BlobSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.BlobSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.BlobSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, blobWriterOverwriteFiles, blobWriterDateTimeFormat, blobWriterAddHeader, copyBehavior)" />
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
        <Parameter Name="blobWriterOverwriteFiles" Type="System.Object" />
        <Parameter Name="blobWriterDateTimeFormat" Type="System.Object" />
        <Parameter Name="blobWriterAddHeader" Type="System.Object" />
        <Parameter Name="copyBehavior" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="writeBatchSize">Schreiben Sie die Batchgröße. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</param>
        <param name="writeBatchTimeout">BatchTimeout zu schreiben. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="sinkRetryCount">Sink Wiederholungsanzahl. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sinkRetryWait">Sink Wiederholung warten. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="blobWriterOverwriteFiles">BLOB-Dateien von Writer überschreiben.
            Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</param>
        <param name="blobWriterDateTimeFormat">BLOB-Writer Datums-/Zeitformat. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="blobWriterAddHeader">BLOB-Writer fügen Header hinzu. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</param>
        <param name="copyBehavior">Der Typ der Kopierverhalten für die Kopie Senke.
            Folgende Werte sind möglich: "PreserveHierarchy", "FlattenHierarchy", "MergeFiles"</param>
        <summary>
            Initialisiert eine neue Instanz der BlobSink-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterAddHeader">
      <MemberSignature Language="C#" Value="public object BlobWriterAddHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BlobWriterAddHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterAddHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterAddHeader As Object" />
      <MemberSignature Language="F#" Value="member this.BlobWriterAddHeader : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterAddHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobWriterAddHeader")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-BLOB-Writer fügen Header hinzu. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterDateTimeFormat">
      <MemberSignature Language="C#" Value="public object BlobWriterDateTimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BlobWriterDateTimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterDateTimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterDateTimeFormat As Object" />
      <MemberSignature Language="F#" Value="member this.BlobWriterDateTimeFormat : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterDateTimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobWriterDateTimeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-BLOB-Writer Datums-/Zeitformat. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterOverwriteFiles">
      <MemberSignature Language="C#" Value="public object BlobWriterOverwriteFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BlobWriterOverwriteFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterOverwriteFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterOverwriteFiles As Object" />
      <MemberSignature Language="F#" Value="member this.BlobWriterOverwriteFiles : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterOverwriteFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobWriterOverwriteFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen von BLOB-Writer überschreiben Dateien. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyBehavior">
      <MemberSignature Language="C#" Value="public string CopyBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.CopyBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property CopyBehavior As String" />
      <MemberSignature Language="F#" Value="member this.CopyBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.CopyBehavior" />
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
            Ruft ab, oder legt ihn fest Kopie Verhaltenstyp für die Kopie Senke. Folgende Werte sind möglich: "PreserveHierarchy", "FlattenHierarchy", "MergeFiles"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>