<Type Name="SqlDWSink" FullName="Microsoft.Azure.Management.DataFactory.Models.SqlDWSink">
  <TypeSignature Language="C#" Value="public class SqlDWSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlDWSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SqlDWSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlDWSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SqlDWSink = class&#xA;    inherit CopySink" />
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
            Eine SQL Data Warehouse-Senke kopieren-Aktivität.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlDWSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.#ctor" />
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
            Initialisiert eine neue Instanz der SqlDWSink-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlDWSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object preCopyScript = null, object allowPolyBase = null, Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings polyBaseSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object preCopyScript, object allowPolyBase, class Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings polyBaseSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SqlDWSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings -&gt; Microsoft.Azure.Management.DataFactory.Models.SqlDWSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.SqlDWSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, preCopyScript, allowPolyBase, polyBaseSettings)" />
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
        <Parameter Name="preCopyScript" Type="System.Object" />
        <Parameter Name="allowPolyBase" Type="System.Object" />
        <Parameter Name="polyBaseSettings" Type="Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="writeBatchSize">Schreiben Sie die Batchgröße. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</param>
        <param name="writeBatchTimeout">BatchTimeout zu schreiben. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="sinkRetryCount">Sink Wiederholungsanzahl. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sinkRetryWait">Sink Wiederholung warten. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="preCopyScript">Vor dem Kopieren der SQL-Skript. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="allowPolyBase">Gibt an, um PolyBase zu verwenden, um Daten in SQL Data Warehouse bei Bedarf zu kopieren. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</param>
        <param name="polyBaseSettings">Gibt PolyBase-bezogenen Einstellungen, wenn AllowPolyBase "true" ist.</param>
        <summary>
            Initialisiert eine neue Instanz der SqlDWSink-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowPolyBase">
      <MemberSignature Language="C#" Value="public object AllowPolyBase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowPolyBase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.AllowPolyBase" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowPolyBase As Object" />
      <MemberSignature Language="F#" Value="member this.AllowPolyBase : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.AllowPolyBase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowPolyBase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, um PolyBase zu verwenden, um Daten in SQL Data Warehouse bei Bedarf zu kopieren. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolyBaseSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings PolyBaseSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings PolyBaseSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.PolyBaseSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property PolyBaseSettings As PolybaseSettings" />
      <MemberSignature Language="F#" Value="member this.PolyBaseSettings : Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.PolyBaseSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="polyBaseSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PolybaseSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt PolyBase-bezogenen Einstellungen auf, wenn AllowPolyBase "true" ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreCopyScript">
      <MemberSignature Language="C#" Value="public object PreCopyScript { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PreCopyScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.PreCopyScript" />
      <MemberSignature Language="VB.NET" Value="Public Property PreCopyScript As Object" />
      <MemberSignature Language="F#" Value="member this.PreCopyScript : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlDWSink.PreCopyScript" />
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
            Ruft ab, oder legt ihn fest SQL vor dem Kopieren-Skript. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>