<Type Name="Transformation" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation">
  <TypeSignature Language="C#" Value="public class Transformation : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Transformation extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
  <TypeSignature Language="VB.NET" Value="Public Class Transformation&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Transformation = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine Transformationsobjekt, enthält alle Informationen, die Transformation für das benannte zugeordnet. Alle Transformationen, die unter einem streamingauftrag enthalten sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Transformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Transformation an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Transformation (string id = null, string name = null, string type = null, Nullable&lt;int&gt; streamingUnits = null, string query = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;int32&gt; streamingUnits, string query, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional streamingUnits As Nullable(Of Integer) = null, Optional query As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Transformation : string * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Transformation (id, name, type, streamingUnits, query, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="streamingUnits" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="streamingUnits">Gibt die Anzahl der streamingeinheiten, die der streamingauftrag verwendet.</param>
        <param name="query">Gibt die Abfrage, die in der streaming-Auftrags ausgeführt werden. Erfahren Sie mehr über den Stream Analytics Query Language (SAQL) hier: https://msdn.microsoft.com/library/azure/dn834998. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="etag">Das aktuelle Entitätstag für die Transformation.
            Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Transformation an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das aktuelle Entitätstag für die Transformation ab. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Abfrage, die in der streaming-Auftrags ausgeführt werden. Erfahren Sie mehr über den Stream Analytics Query Language (SAQL) hier: https://msdn.microsoft.com/library/azure/dn834998.
            Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamingUnits">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StreamingUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StreamingUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.StreamingUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamingUnits As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StreamingUnits : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.StreamingUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.streamingUnits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Anzahl der streamingeinheiten, die der streamingauftrag verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>