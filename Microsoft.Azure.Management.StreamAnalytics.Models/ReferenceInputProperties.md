<Type Name="ReferenceInputProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties">
  <TypeSignature Language="C#" Value="public class ReferenceInputProperties : Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReferenceInputProperties extends Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ReferenceInputProperties&#xA;Inherits InputProperties" />
  <TypeSignature Language="F#" Value="type ReferenceInputProperties = class&#xA;    inherit InputProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Reference")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Eigenschaften, die mit der Eingabe mit Verweisdaten verknüpft sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReferenceInputProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ReferenceInputProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReferenceInputProperties (Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization = null, Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics = null, string etag = null, Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource datasource = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization, class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics, string etag, class Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource datasource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties.#ctor(Microsoft.Azure.Management.StreamAnalytics.Models.Serialization,Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization * Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics * string * Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties (serialization, diagnostics, etag, datasource)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serialization" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
        <Parameter Name="diagnostics" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="datasource" Type="Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource" />
      </Parameters>
      <Docs>
        <param name="serialization">Beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten serialisiert werden, wenn an die Ausgabe geschrieben.
            Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="diagnostics">Beschreibt die Bedingungen für die Eingabe, Ausgabe oder des Auftrags insgesamt, die Kunden ein Eingreifen erforderlich machen.</param>
        <param name="etag">Das aktuelle Entitätstag für die Eingabe. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</param>
        <param name="datasource">Beschreibt eine Eingabedatenquelle, die Verweisdaten enthält. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <summary>
            Initialisiert eine neue Instanz der ReferenceInputProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource Datasource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource Datasource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties.Datasource" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasource As ReferenceInputDataSource" />
      <MemberSignature Language="F#" Value="member this.Datasource : Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputProperties.Datasource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="datasource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt beschreibt ein Eingabedatenquelle, die Verweisdaten enthält. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>