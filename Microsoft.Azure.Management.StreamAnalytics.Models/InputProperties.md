<Type Name="InputProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties">
  <TypeSignature Language="C#" Value="public class InputProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InputProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class InputProperties" />
  <TypeSignature Language="F#" Value="type InputProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften, die mit einer Eingabe zugewiesen sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der InputProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputProperties (Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization = null, Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization, class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.#ctor(Microsoft.Azure.Management.StreamAnalytics.Models.Serialization,Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization * Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties (serialization, diagnostics, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serialization" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
        <Parameter Name="diagnostics" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serialization">Beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten serialisiert werden, wenn an die Ausgabe geschrieben.
            Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="diagnostics">Beschreibt die Bedingungen für die Eingabe, Ausgabe oder des Auftrags insgesamt, die Kunden ein Eingreifen erforderlich machen.</param>
        <param name="etag">Das aktuelle Entitätstag für die Eingabe. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der InputProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As Diagnostics" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft beschreibt Bedingungen, die für die Eingabe, Ausgabe oder den gesamten Auftrag, garantieren, dass Kunden Ihre Aufmerksamkeit.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das aktuelle Entitätstag für die Eingabe ab. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Serialization" />
      <MemberSignature Language="VB.NET" Value="Public Property Serialization As Serialization" />
      <MemberSignature Language="F#" Value="member this.Serialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Serialization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serialization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten serialisiert werden, wenn an die Ausgabe geschrieben. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>