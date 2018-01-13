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
            Eine SQL Data Warehouse-Quelle kopieren-Aktivität.
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
            Initialisiert eine neue Instanz der SqlDWSource-Klasse.
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
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="sourceRetryCount">Anzahl von Wiederholungsversuchen Quelle. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sourceRetryWait">Warten Sie Quelle, versuchen Sie es erneut. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="sqlReaderQuery">SQL Data Warehouse-Reader-Abfrage. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="sqlReaderStoredProcedureName">Der Name der gespeicherten Prozedur für eine SQL Data Warehouse-Datenquelle. Dies kann nicht gleichzeitig als die SqlReaderQuery verwendet werden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="storedProcedureParameters">Wert und Typ für Parameter gespeicherter Prozeduren festlegen. Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}". Typ: Objekt (oder Ausdruck mit ResultType-Objekt), ItemType: StoredProcedureParameter.</param>
        <summary>
            Initialisiert eine neue Instanz der SqlDWSource-Klasse.
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
            Ruft ab, oder legt ihn fest SQL Data Warehouse-Reader-Abfrage. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Ruft ab oder legt den Namen der gespeicherten Prozedur für eine SQL Data Warehouse-Datenquelle fest. Dies kann nicht gleichzeitig als die SqlReaderQuery verwendet werden.
            Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Ruft ab, oder legt sie fest, Wert und Typ für Parameter gespeicherter Prozeduren festlegen. Beispiel: "{Parameter1: {Wert:"1", Typ:"Int"}}".
            Typ: Objekt (oder Ausdruck mit ResultType-Objekt), ItemType: StoredProcedureParameter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>