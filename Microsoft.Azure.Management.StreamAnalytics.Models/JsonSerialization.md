<Type Name="JsonSerialization" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization">
  <TypeSignature Language="C#" Value="public class JsonSerialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonSerialization extends Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonSerialization&#xA;Inherits Serialization" />
  <TypeSignature Language="F#" Value="type JsonSerialization = class&#xA;    inherit Serialization" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Json")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten beim Schreiben in eine Ausgabe im JSON-Format serialisiert werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonSerialization ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse JsonSerialization an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonSerialization (string encoding = null, string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string encoding, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional encoding As String = null, Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization : string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization (encoding, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encoding" Type="System.String" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encoding">Gibt die Codierung der eingehenden Daten bei der Eingabe und die Codierung der ausgehenden Daten im Fall von Ausgabe. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich. Folgende Werte sind möglich: 'UTF8'</param>
        <param name="format">Diese Eigenschaft gilt nur für JSON-Serialisierung, der nur Ausgaben auf. Es gilt nicht für Eingaben. Diese Eigenschaft gibt das Format der JSON-Ausgabe geschrieben werden soll. Die derzeit unterstützten Werte sind "LineSeparated" zeigt an, dass die Ausgabe so formatiert wird, dass jedes JSON-Objekt, das durch eine neue Zeile und "Array" zeigt an, dass die Ausgabe als Array von JSON-Objekten formatiert wird getrennt. Standardwert ist "LineSeparated", wenn der Wert NULL. Folgende Werte sind möglich: "LineSeparated", "Array"</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse JsonSerialization an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public string Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As String" />
      <MemberSignature Language="F#" Value="member this.Encoding : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Codierung der eingehenden Daten bei der Eingabe und die Codierung der ausgehenden Daten im Fall von Ausgabe. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich. Folgende Werte sind möglich: 'UTF8'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JsonSerialization.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt diese Eigenschaft gilt nur JSON-Serialisierung von nur Ausgaben. Es gilt nicht für Eingaben. Diese Eigenschaft gibt das Format der JSON-Ausgabe geschrieben werden soll. Die derzeit unterstützten Werte sind "LineSeparated" zeigt an, dass die Ausgabe so formatiert wird, dass jedes JSON-Objekt, das durch eine neue Zeile und "Array" zeigt an, dass die Ausgabe als Array von JSON-Objekten formatiert wird getrennt. Standardwert ist "LineSeparated", wenn der Wert NULL. Folgende Werte sind möglich: "LineSeparated", "Array"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>