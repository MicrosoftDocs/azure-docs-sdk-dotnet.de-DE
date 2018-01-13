<Type Name="AzureTableSink" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink">
  <TypeSignature Language="C#" Value="public class AzureTableSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type AzureTableSink = class&#xA;    inherit CopySink" />
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
            Eine Kopie Aktivität Azure Table-Senke.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.#ctor" />
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
            Initialisiert eine neue Instanz der AzureTableSink-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object azureTableDefaultPartitionKeyValue = null, object azureTablePartitionKeyName = null, object azureTableRowKeyName = null, object azureTableInsertType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object azureTableDefaultPartitionKeyValue, object azureTablePartitionKeyName, object azureTableRowKeyName, object azureTableInsertType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional azureTableDefaultPartitionKeyValue As Object = null, Optional azureTablePartitionKeyName As Object = null, Optional azureTableRowKeyName As Object = null, Optional azureTableInsertType As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureTableSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, azureTableDefaultPartitionKeyValue, azureTablePartitionKeyName, azureTableRowKeyName, azureTableInsertType)" />
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
        <Parameter Name="azureTableDefaultPartitionKeyValue" Type="System.Object" />
        <Parameter Name="azureTablePartitionKeyName" Type="System.Object" />
        <Parameter Name="azureTableRowKeyName" Type="System.Object" />
        <Parameter Name="azureTableInsertType" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="writeBatchSize">Schreiben Sie die Batchgröße. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</param>
        <param name="writeBatchTimeout">BatchTimeout zu schreiben. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="sinkRetryCount">Sink Wiederholungsanzahl. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sinkRetryWait">Sink Wiederholung warten. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="azureTableDefaultPartitionKeyValue">Azure Tabelle standardmäßiger partitionsschlüsselwert. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="azureTablePartitionKeyName">Azure Tabelle Partition Schlüsselname. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="azureTableRowKeyName">Azure Tabelle Zeile Schlüsselname. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="azureTableInsertType">Typ wird von Azure-Tabelle einfügen. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der AzureTableSink-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableDefaultPartitionKeyValue">
      <MemberSignature Language="C#" Value="public object AzureTableDefaultPartitionKeyValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableDefaultPartitionKeyValue As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableDefaultPartitionKeyValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableDefaultPartitionKeyValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Azure Tabelle standardmäßiger partitionsschlüsselwert. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableInsertType">
      <MemberSignature Language="C#" Value="public object AzureTableInsertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableInsertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableInsertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableInsertType As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableInsertType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableInsertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableInsertType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Azure Tabelle einfügen. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTablePartitionKeyName">
      <MemberSignature Language="C#" Value="public object AzureTablePartitionKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTablePartitionKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTablePartitionKeyName As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTablePartitionKeyName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTablePartitionKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Azure Tabelle Partition Schlüsselnamen. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableRowKeyName">
      <MemberSignature Language="C#" Value="public object AzureTableRowKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableRowKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableRowKeyName As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableRowKeyName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableRowKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Azure Tabelle Zeile Schlüsselnamen. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>