<Type Name="HdfsSource" FullName="Microsoft.Azure.Management.DataFactory.Models.HdfsSource">
  <TypeSignature Language="C#" Value="public class HdfsSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HdfsSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HdfsSource" />
  <TypeSignature Language="VB.NET" Value="Public Class HdfsSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type HdfsSource = class&#xA;    inherit CopySource" />
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
            Eine HDFS-Quelle kopieren-Aktivität.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HdfsSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.#ctor" />
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
            Initialisiert eine neue Instanz der HdfsSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HdfsSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object recursive = null, Microsoft.Azure.Management.DataFactory.Models.DistcpSettings distcpSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object recursive, class Microsoft.Azure.Management.DataFactory.Models.DistcpSettings distcpSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DistcpSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HdfsSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DistcpSettings -&gt; Microsoft.Azure.Management.DataFactory.Models.HdfsSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.HdfsSource (additionalProperties, sourceRetryCount, sourceRetryWait, recursive, distcpSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="recursive" Type="System.Object" />
        <Parameter Name="distcpSettings" Type="Microsoft.Azure.Management.DataFactory.Models.DistcpSettings" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="sourceRetryCount">Anzahl von Wiederholungsversuchen Quelle. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</param>
        <param name="sourceRetryWait">Warten Sie Quelle, versuchen Sie es erneut. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="recursive">Bei "true", werden Dateien unter dem Ordnerpfad rekursiv gelesen werden. Der Standardwert ist true. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</param>
        <param name="distcpSettings">Gibt die Distcp-bezogene Einstellungen.</param>
        <summary>
            Initialisiert eine neue Instanz der HdfsSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistcpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DistcpSettings DistcpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DistcpSettings DistcpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.DistcpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DistcpSettings As DistcpSettings" />
      <MemberSignature Language="F#" Value="member this.DistcpSettings : Microsoft.Azure.Management.DataFactory.Models.DistcpSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HdfsSource.DistcpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distcpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DistcpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt Distcp-bezogenen Einstellungen an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public object Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Object" />
      <MemberSignature Language="F#" Value="member this.Recursive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HdfsSource.Recursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob "true" werden Dateien unter dem Ordnerpfad rekursiv gelesen werden. Der Standardwert ist true. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="hdfsSource.Validate " />
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