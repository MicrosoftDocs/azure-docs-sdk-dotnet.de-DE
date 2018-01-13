<Type Name="Output" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Output">
  <TypeSignature Language="C#" Value="public class Output : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Output extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
  <TypeSignature Language="VB.NET" Value="Public Class Output&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Output = class&#xA;    inherit SubResource" />
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
            Einem Ausgabeobjekt, enthält alle Informationen, die die benannten Ausgabe zugeordnet. Alle Ausgaben, die unter einem streamingauftrag enthalten sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Output ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Output.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Ausgabeklasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Output (string id = null, string name = null, string type = null, Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource datasource = null, Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization = null, Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource datasource, class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization, class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Output.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource,Microsoft.Azure.Management.StreamAnalytics.Models.Serialization,Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Output : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource * Microsoft.Azure.Management.StreamAnalytics.Models.Serialization * Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Output (id, name, type, datasource, serialization, diagnostics, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="datasource" Type="Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
        <Parameter Name="serialization" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
        <Parameter Name="diagnostics" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="datasource">Beschreibt die Datenquelle, der Ausgabe geschrieben wird. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="serialization">Beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten serialisiert werden, wenn an die Ausgabe geschrieben.
            Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="diagnostics">Beschreibt die Bedingungen für die Eingabe, Ausgabe oder des Auftrags insgesamt, die Kunden ein Eingreifen erforderlich machen.</param>
        <param name="etag">Das aktuelle Entitätstag für die Ausgabe. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der Ausgabeklasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource Datasource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource Datasource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Datasource" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasource As OutputDataSource" />
      <MemberSignature Language="F#" Value="member this.Datasource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Datasource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.datasource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt beschreibt die Datenquelle, der Ausgabe geschrieben wird. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As Diagnostics" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnostics")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Etag" />
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
            Ruft das aktuelle Entitätstag für die Ausgabe an. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Serialization" />
      <MemberSignature Language="VB.NET" Value="Public Property Serialization As Serialization" />
      <MemberSignature Language="F#" Value="member this.Serialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Serialization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialization")</AttributeName>
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