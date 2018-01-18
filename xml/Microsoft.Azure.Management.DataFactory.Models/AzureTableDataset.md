<Type Name="AzureTableDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset">
  <TypeSignature Language="C#" Value="public class AzureTableDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type AzureTableDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureTable")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="70ae0-101">Das Azure Table Storage-Dataset.</span><span class="sxs-lookup"><span data-stu-id="70ae0-101">The Azure Table storage dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset.#ctor" />
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
            <span data-ttu-id="70ae0-102">Initialisiert eine neue Instanz der AzureTableDataset-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70ae0-102">Initializes a new instance of the AzureTableDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object tableName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object tableName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, tableName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset (linkedServiceName, tableName, additionalProperties, description, structure, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="tableName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="70ae0-103">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="70ae0-103">Linked service reference.</span></span></param>
        <param name="tableName"><span data-ttu-id="70ae0-104">Der Tabellenname der Azure-Tabellenspeicher.</span><span class="sxs-lookup"><span data-stu-id="70ae0-104">The table name of the Azure Table storage.</span></span>
            <span data-ttu-id="70ae0-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="70ae0-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="70ae0-106">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="70ae0-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="70ae0-107">Beschreibung des Datasets.</span><span class="sxs-lookup"><span data-stu-id="70ae0-107">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="70ae0-108">Spalten, die die Struktur des Datasets zu definieren.</span><span class="sxs-lookup"><span data-stu-id="70ae0-108">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="70ae0-109">Typ: Array (oder Ausdruck mit ResultType-Array), ItemType: DatasetDataElement.</span><span class="sxs-lookup"><span data-stu-id="70ae0-109">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="70ae0-110">Parameter für das Dataset.</span><span class="sxs-lookup"><span data-stu-id="70ae0-110">Parameters for dataset.</span></span></param>
        <summary>
            <span data-ttu-id="70ae0-111">Initialisiert eine neue Instanz der AzureTableDataset-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70ae0-111">Initializes a new instance of the AzureTableDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public object TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As Object" />
      <MemberSignature Language="F#" Value="member this.TableName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70ae0-112">Ruft ab oder legt den Tabellennamen der Azure-Tabellenspeicher.</span><span class="sxs-lookup"><span data-stu-id="70ae0-112">Gets or sets the table name of the Azure Table storage.</span></span> <span data-ttu-id="70ae0-113">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="70ae0-113">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureTableDataset.Validate " />
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
            <span data-ttu-id="70ae0-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="70ae0-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="70ae0-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="70ae0-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>