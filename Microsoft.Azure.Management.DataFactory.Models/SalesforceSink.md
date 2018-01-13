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
            Eine Salesforce-Senke kopieren-Aktivität.
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
            Initialisiert eine neue Instanz der SalesforceSink-Klasse.
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
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="writeBatchSize">Schreiben Sie die Batchgröße. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</param>
        <param name="writeBatchTimeout">BatchTimeout zu schreiben. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="sinkRetryCount">Sink Wiederholungsanzahl. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sinkRetryWait">Sink Wiederholung warten. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="writeBehavior">Das Schreibverhalten für den Vorgang.
            Standardmäßig ist ein Einfügevorgang. Folgende Werte sind möglich: 'Insert', "Upsert"</param>
        <param name="externalIdFieldName">Der Name des externen ID-Felds für den upsert-Vorgang. Standardwert ist 'Id'-Spalte. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="ignoreNullValues">Das Flag, das anzeigt, ob ignorieren null-Werte aus dem Eingabedataset (außer Schlüsselfelder) während der Schreibvorgang. Der Standardwert ist „false“. Wenn legen Sie sie auf "true" bedeutet, dass ADF werden die Daten in das Zielobjekt beim Ausführen von Upsert/Update-Vorgang unverändert belassen und definierten Standardwert einzufügen, wenn auf diese Weise Einfügevorgang im Vergleich zu ADF der Daten in das Zielobjekt auf NULL wird beim Ausführen von Upsert aktualisieren / Vorgang zum Aktualisieren und Einfügen von NULL-Wert, bei der Insert-Vorgang. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</param>
        <summary>
            Initialisiert eine neue Instanz der SalesforceSink-Klasse.
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
            Ruft ab oder legt den Namen des externen ID-Felds für Upsert-Vorgang. Standardwert ist 'Id'-Spalte. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Ruft ab oder legt das Flag, das anzeigt, ob null-Werte aus dem Eingabedataset (außer Schlüsselfelder) beim Schreibvorgang ignoriert werden sollen. Der Standardwert ist „false“. Wenn legen Sie sie auf "true" bedeutet, dass ADF werden die Daten in das Zielobjekt beim Ausführen von Upsert/Update-Vorgang unverändert belassen und definierten Standardwert einzufügen, wenn auf diese Weise Einfügevorgang im Vergleich zu ADF der Daten in das Zielobjekt auf NULL wird beim Ausführen von Upsert aktualisieren / Vorgang zum Aktualisieren und Einfügen von NULL-Wert, bei der Insert-Vorgang. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).
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
            Ruft ab oder legt das Verhalten der Schreibzugriff für den Vorgang. Standardmäßig ist ein Einfügevorgang. Folgende Werte sind möglich: 'Insert', "Upsert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>