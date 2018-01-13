<Type Name="FileShareDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.FileShareDataset">
  <TypeSignature Language="C#" Value="public class FileShareDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileShareDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class FileShareDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type FileShareDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("FileShare")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein System-Dataset einer lokalen Datei.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileShareDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.#ctor" />
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
            Initialisiert eine neue Instanz der FileShareDataset-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileShareDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object folderPath = null, object fileName = null, Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format = null, object fileFilter = null, Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object folderPath, object fileName, class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format, object fileFilter, class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat,System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetCompression)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional folderPath As Object = null, Optional fileName As Object = null, Optional format As DatasetStorageFormat = null, Optional fileFilter As Object = null, Optional compression As DatasetCompression = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.FileShareDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetCompression -&gt; Microsoft.Azure.Management.DataFactory.Models.FileShareDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.FileShareDataset (linkedServiceName, additionalProperties, description, structure, parameters, folderPath, fileName, format, fileFilter, compression)" />
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
        <Parameter Name="folderPath" Type="System.Object" />
        <Parameter Name="fileName" Type="System.Object" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
        <Parameter Name="fileFilter" Type="System.Object" />
        <Parameter Name="compression" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName">Verknüpften Dienst verweisen.</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung des Datasets.</param>
        <param name="structure">Spalten, die die Struktur des Datasets zu definieren. Typ: Array (oder Ausdruck mit ResultType-Array), ItemType: DatasetDataElement.</param>
        <param name="parameters">Parameter für das Dataset.</param>
        <param name="folderPath">Der Pfad des lokalen Dateisystems.
            Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="fileName">Der Name des lokalen Dateisystems.
            Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="format">Das Format der Dateien.</param>
        <param name="fileFilter">Geben Sie einen Filter zur Auswahl einer Teilmenge der Dateien in "folderPath" statt alle Dateien an. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="compression">Die datenkomprimierungsmethode für das Dateisystem verwendet.</param>
        <summary>
            Initialisiert eine neue Instanz der FileShareDataset-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As DatasetCompression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.Compression" />
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
            Ruft ab oder legt die datenkomprimierungsmethode für das Dateisystem verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileFilter">
      <MemberSignature Language="C#" Value="public object FileFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FileFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.FileFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property FileFilter As Object" />
      <MemberSignature Language="F#" Value="member this.FileFilter : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.FileFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.fileFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt angeben einen Filter verwendet werden soll, wählen Sie eine Teilmenge der Dateien in der FolderPath anstatt alle Dateien. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public object FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As Object" />
      <MemberSignature Language="F#" Value="member this.FileName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.FileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.fileName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der dem lokalen Dateisystem. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public object FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As Object" />
      <MemberSignature Language="F#" Value="member this.FolderPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.folderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad für das lokale Dateisystem. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As DatasetStorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.Format" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileShareDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="fileShareDataset.Validate " />
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