<Type Name="AmazonRedshiftSource" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource">
  <TypeSignature Language="C#" Value="public class AmazonRedshiftSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonRedshiftSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonRedshiftSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type AmazonRedshiftSource = class&#xA;    inherit CopySource" />
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
            Eine Aktivität Kopiequelle Amazon Redshift-Quelle.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.#ctor" />
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
            Initialisiert eine neue Instanz der AmazonRedshiftSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object query = null, Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings redshiftUnloadSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object query, class Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings redshiftUnloadSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource (additionalProperties, sourceRetryCount, sourceRetryWait, query, redshiftUnloadSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="query" Type="System.Object" />
        <Parameter Name="redshiftUnloadSettings" Type="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="sourceRetryCount">Anzahl von Wiederholungsversuchen Quelle. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sourceRetryWait">Warten Sie Quelle, versuchen Sie es erneut. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="query">Datenbankabfrage. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="redshiftUnloadSettings">Die Amazon S3 Einstellungen für die zwischenzeitliche Amazon S3 beim Kopieren von Amazon Redshift mit entladen zu können. Mit dieser Option können werden Daten von Amazon Redshift-Quelle zuerst in S3 entladen und dann in die entsprechenden Senke von interim S3 kopiert.</param>
        <summary>
            Initialisiert eine neue Instanz der AmazonRedshiftSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public object Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As Object" />
      <MemberSignature Language="F#" Value="member this.Query : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die Datenbankabfrage fest. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedshiftUnloadSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings RedshiftUnloadSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings RedshiftUnloadSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.RedshiftUnloadSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property RedshiftUnloadSettings As RedshiftUnloadSettings" />
      <MemberSignature Language="F#" Value="member this.RedshiftUnloadSettings : Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.RedshiftUnloadSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="redshiftUnloadSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Amazon S3 Einstellungen für die zwischenzeitliche Amazon S3 beim Kopieren von Amazon Redshift mit entladen. Mit dieser Option können werden Daten von Amazon Redshift-Quelle zuerst in S3 entladen und dann in die entsprechenden Senke von interim S3 kopiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="amazonRedshiftSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>