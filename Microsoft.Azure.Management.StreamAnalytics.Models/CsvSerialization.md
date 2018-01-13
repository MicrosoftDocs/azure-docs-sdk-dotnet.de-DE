<Type Name="CsvSerialization" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization">
  <TypeSignature Language="C#" Value="public class CsvSerialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsvSerialization extends Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization" />
  <TypeSignature Language="VB.NET" Value="Public Class CsvSerialization&#xA;Inherits Serialization" />
  <TypeSignature Language="F#" Value="type CsvSerialization = class&#xA;    inherit Serialization" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Csv")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="10ddf-101">Beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten beim Schreiben in eine Ausgabe im CSV-Format serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="10ddf-101">Describes how data from an input is serialized or how data is serialized when written to an output in CSV format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsvSerialization ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10ddf-102">Initialisiert eine neue Instanz der CsvSerialization-Klasse.</span><span class="sxs-lookup"><span data-stu-id="10ddf-102">Initializes a new instance of the CsvSerialization class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsvSerialization (string fieldDelimiter = null, string encoding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldDelimiter, string encoding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fieldDelimiter As String = null, Optional encoding As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization : string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization (fieldDelimiter, encoding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldDelimiter" Type="System.String" />
        <Parameter Name="encoding" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fieldDelimiter"><span data-ttu-id="10ddf-103">Gibt das Trennzeichen an, das zum Trennen von Datensätzen durch Trennzeichen getrennte Werten (CSV) verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="10ddf-103">Specifies the delimiter that will be used to separate comma-separated value (CSV) records.</span></span> <span data-ttu-id="10ddf-104">Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output eine Liste der unterstützten Werte.</span><span class="sxs-lookup"><span data-stu-id="10ddf-104">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a list of supported values.</span></span> <span data-ttu-id="10ddf-105">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="10ddf-105">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="encoding"><span data-ttu-id="10ddf-106">Gibt die Codierung der eingehenden Daten bei der Eingabe und die Codierung der ausgehenden Daten im Fall von Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="10ddf-106">Specifies the encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output.</span></span> <span data-ttu-id="10ddf-107">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="10ddf-107">Required on PUT (CreateOrReplace) requests.</span></span> <span data-ttu-id="10ddf-108">Folgende Werte sind möglich: 'UTF8'</span><span class="sxs-lookup"><span data-stu-id="10ddf-108">Possible values include: 'UTF8'</span></span></param>
        <summary>
            <span data-ttu-id="10ddf-109">Initialisiert eine neue Instanz der CsvSerialization-Klasse.</span><span class="sxs-lookup"><span data-stu-id="10ddf-109">Initializes a new instance of the CsvSerialization class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public string Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As String" />
      <MemberSignature Language="F#" Value="member this.Encoding : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.Encoding" />
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
            <span data-ttu-id="10ddf-110">Ruft ab oder legt gibt die Codierung der eingehenden Daten bei der Eingabe und die Codierung der ausgehenden Daten im Fall von Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="10ddf-110">Gets or sets specifies the encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output.</span></span> <span data-ttu-id="10ddf-111">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="10ddf-111">Required on PUT (CreateOrReplace) requests.</span></span> <span data-ttu-id="10ddf-112">Folgende Werte sind möglich: 'UTF8'</span><span class="sxs-lookup"><span data-stu-id="10ddf-112">Possible values include: 'UTF8'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FieldDelimiter">
      <MemberSignature Language="C#" Value="public string FieldDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FieldDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.FieldDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property FieldDelimiter As String" />
      <MemberSignature Language="F#" Value="member this.FieldDelimiter : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.FieldDelimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fieldDelimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10ddf-113">Ruft ab oder legt gibt das Trennzeichen an, das zum Trennen von Datensätzen durch Trennzeichen getrennte Werten (CSV) verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="10ddf-113">Gets or sets specifies the delimiter that will be used to separate comma-separated value (CSV) records.</span></span> <span data-ttu-id="10ddf-114">Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output eine Liste der unterstützten Werte.</span><span class="sxs-lookup"><span data-stu-id="10ddf-114">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a list of supported values.</span></span> <span data-ttu-id="10ddf-115">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="10ddf-115">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>