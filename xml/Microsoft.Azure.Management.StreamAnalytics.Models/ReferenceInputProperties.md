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
            <span data-ttu-id="a6be3-101">Die Eigenschaften, die mit der Eingabe mit Verweisdaten verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="a6be3-101">The properties that are associated with an input containing reference data.</span></span>
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
            <span data-ttu-id="a6be3-102">Initialisiert eine neue Instanz der ReferenceInputProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6be3-102">Initializes a new instance of the ReferenceInputProperties class.</span></span>
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
        <param name="serialization"><span data-ttu-id="a6be3-103">Beschreibt, wie Daten aus einer Eingabe serialisiert werden, oder wie die Daten serialisiert werden, wenn an die Ausgabe geschrieben.</span><span class="sxs-lookup"><span data-stu-id="a6be3-103">Describes how data from an input is serialized or how data is serialized when written to an output.</span></span>
            <span data-ttu-id="a6be3-104">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6be3-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="diagnostics"><span data-ttu-id="a6be3-105">Beschreibt die Bedingungen für die Eingabe, Ausgabe oder des Auftrags insgesamt, die Kunden ein Eingreifen erforderlich machen.</span><span class="sxs-lookup"><span data-stu-id="a6be3-105">Describes conditions applicable to the Input, Output, or the job overall, that warrant customer attention.</span></span></param>
        <param name="etag"><span data-ttu-id="a6be3-106">Das aktuelle Entitätstag für die Eingabe.</span><span class="sxs-lookup"><span data-stu-id="a6be3-106">The current entity tag for the input.</span></span> <span data-ttu-id="a6be3-107">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="a6be3-107">This is an opaque string.</span></span> <span data-ttu-id="a6be3-108">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="a6be3-108">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="a6be3-109">Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</span><span class="sxs-lookup"><span data-stu-id="a6be3-109">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <param name="datasource"><span data-ttu-id="a6be3-110">Beschreibt eine Eingabedatenquelle, die Verweisdaten enthält.</span><span class="sxs-lookup"><span data-stu-id="a6be3-110">Describes an input data source that contains reference data.</span></span> <span data-ttu-id="a6be3-111">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6be3-111">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <summary>
            <span data-ttu-id="a6be3-112">Initialisiert eine neue Instanz der ReferenceInputProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6be3-112">Initializes a new instance of the ReferenceInputProperties class.</span></span>
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
            <span data-ttu-id="a6be3-113">Ruft ab oder legt beschreibt ein Eingabedatenquelle, die Verweisdaten enthält.</span><span class="sxs-lookup"><span data-stu-id="a6be3-113">Gets or sets describes an input data source that contains reference data.</span></span> <span data-ttu-id="a6be3-114">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6be3-114">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>