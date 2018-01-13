<Type Name="HttpDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.HttpDataset">
  <TypeSignature Language="C#" Value="public class HttpDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HttpDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type HttpDataset = class&#xA;    inherit Dataset" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Dataset</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("HttpFile")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine Datei in einen HTTP-Web-Server.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.#ctor" />
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
            Initialisiert eine neue Instanz der HttpDataset-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object relativeUrl = null, object requestMethod = null, object requestBody = null, object additionalHeaders = null, Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format = null, Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object relativeUrl, object requestMethod, object requestBody, object additionalHeaders, class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format, class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat,Microsoft.Azure.Management.DataFactory.Models.DatasetCompression)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional relativeUrl As Object = null, Optional requestMethod As Object = null, Optional requestBody As Object = null, Optional additionalHeaders As Object = null, Optional format As DatasetStorageFormat = null, Optional compression As DatasetCompression = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HttpDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat * Microsoft.Azure.Management.DataFactory.Models.DatasetCompression -&gt; Microsoft.Azure.Management.DataFactory.Models.HttpDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.HttpDataset (linkedServiceName, additionalProperties, description, structure, parameters, relativeUrl, requestMethod, requestBody, additionalHeaders, format, compression)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
        <Parameter Name="relativeUrl" Type="System.Object" />
        <Parameter Name="requestMethod" Type="System.Object" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="additionalHeaders" Type="System.Object" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
        <Parameter Name="compression" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName">Verknüpften Dienst verweisen.</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung des Datasets.</param>
        <param name="structure">Spalten, die die Struktur des Datasets zu definieren. Typ: Array (oder Ausdruck mit ResultType-Array), ItemType: DatasetDataElement.</param>
        <param name="parameters">Parameter für das Dataset.</param>
        <param name="relativeUrl">Die relative URL basierend auf der URL in die HttpLinkedService bezieht sich auf eine HTTP-Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="requestMethod">Die HTTP-Methode für die HTTP-Anforderung.
            Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="requestBody">Der Text der HTTP-Anforderung. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="additionalHeaders">Die Header für die HTTP-Anforderung.
            z. B. Request-header-name-1:request-header-value-1... request-header-name-n:request-header-value-n Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="format">Das Format der Dateien.</param>
        <param name="compression">Die datenkomprimierungsmethode für Dateien verwendet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der HttpDataset-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalHeaders">
      <MemberSignature Language="C#" Value="public object AdditionalHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AdditionalHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.AdditionalHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalHeaders As Object" />
      <MemberSignature Language="F#" Value="member this.AdditionalHeaders : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.AdditionalHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.additionalHeaders")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Header für die HTTP-Anforderung. z. B. Request-header-name-1:request-header-value-1... request-header-name-n:request-header-value-n Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As DatasetCompression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Compression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetCompression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die datenkomprimierungsmethode für Dateien verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As DatasetStorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Format der Dateien.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeUrl">
      <MemberSignature Language="C#" Value="public object RelativeUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RelativeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RelativeUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeUrl As Object" />
      <MemberSignature Language="F#" Value="member this.RelativeUrl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RelativeUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.relativeUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die die relative URL basierend auf der URL in die HttpLinkedService bezieht sich auf eine HTTP-Dateityp: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestBody">
      <MemberSignature Language="C#" Value="public object RequestBody { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RequestBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestBody" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestBody As Object" />
      <MemberSignature Language="F#" Value="member this.RequestBody : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.requestBody")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Text der HTTP-Anforderung. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestMethod">
      <MemberSignature Language="C#" Value="public object RequestMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RequestMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestMethod As Object" />
      <MemberSignature Language="F#" Value="member this.RequestMethod : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.requestMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den HTTP-Methode für die HTTP-Anforderung. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="httpDataset.Validate " />
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