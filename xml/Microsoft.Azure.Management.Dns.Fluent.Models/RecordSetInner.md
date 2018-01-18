<Type Name="RecordSetInner" FullName="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner">
  <TypeSignature Language="C#" Value="public class RecordSetInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecordSetInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RecordSetInner" />
  <TypeSignature Language="F#" Value="type RecordSetInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f006c-101">Beschreibt eine DNS-Datensatz (eine Sammlung von DNS-Einträge mit dem gleichen Namen und Typ).</span><span class="sxs-lookup"><span data-stu-id="f006c-101">Describes a DNS record set (a collection of DNS records with the same name and type).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecordSetInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f006c-102">Initialisiert eine neue Instanz der RecordSetInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f006c-102">Initializes a new instance of the RecordSetInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecordSetInner (string id = null, string name = null, string type = null, string etag = null, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Nullable&lt;long&gt; tTL = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; aRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; aaaaRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; mxRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; nsRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; ptrRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; srvRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; txtRecords = null, Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord cnameRecord = null, Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord soaRecord = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, valuetype System.Nullable`1&lt;int64&gt; tTL, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; aRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; aaaaRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; mxRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; nsRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; ptrRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; srvRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; txtRecords, class Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord cnameRecord, class Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord soaRecord) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int64},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.ARecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord},Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord,Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; * Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord * Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord -&gt; Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" Usage="new Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner (id, name, type, etag, metadata, tTL, aRecords, aaaaRecords, mxRecords, nsRecords, ptrRecords, srvRecords, txtRecords, cnameRecord, soaRecord)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tTL" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="aRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt;" />
        <Parameter Name="aaaaRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt;" />
        <Parameter Name="mxRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt;" />
        <Parameter Name="nsRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt;" />
        <Parameter Name="ptrRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt;" />
        <Parameter Name="srvRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt;" />
        <Parameter Name="txtRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt;" />
        <Parameter Name="cnameRecord" Type="Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord" />
        <Parameter Name="soaRecord" Type="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f006c-103">Die ID des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f006c-103">The ID of the record set.</span></span></param>
        <param name="name"><span data-ttu-id="f006c-104">Der Name des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f006c-104">The name of the record set.</span></span></param>
        <param name="type"><span data-ttu-id="f006c-105">Der Typ des Datensatzes gesetzt.</span><span class="sxs-lookup"><span data-stu-id="f006c-105">The type of the record set.</span></span></param>
        <param name="etag"><span data-ttu-id="f006c-106">Das Etag des Datensatzes festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f006c-106">The etag of the record set.</span></span></param>
        <param name="metadata"><span data-ttu-id="f006c-107">Legen Sie die Metadaten, die auf den Datensatz angefügt.</span><span class="sxs-lookup"><span data-stu-id="f006c-107">The metadata attached to the record set.</span></span></param>
        <param name="tTL"><span data-ttu-id="f006c-108">Die Gültigkeitsdauer (Time-to-live) der Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-108">The TTL (time-to-live) of the records in the record set.</span></span></param>
        <param name="aRecords"><span data-ttu-id="f006c-109">Die Liste von A-Einträgen im Datensatz festgelegt.</span><span class="sxs-lookup"><span data-stu-id="f006c-109">The list of A records in the record set.</span></span></param>
        <param name="aaaaRecords"><span data-ttu-id="f006c-110">Die Liste der AAAA-Datensätze in den Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-110">The list of AAAA records in the record set.</span></span></param>
        <param name="mxRecords"><span data-ttu-id="f006c-111">Die Liste der MX-Einträge in den Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-111">The list of MX records in the record set.</span></span></param>
        <param name="nsRecords"><span data-ttu-id="f006c-112">Die Liste der NS-Datensätze in den Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-112">The list of NS records in the record set.</span></span></param>
        <param name="ptrRecords"><span data-ttu-id="f006c-113">Die Liste der PTR-Einträge in den Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-113">The list of PTR records in the record set.</span></span></param>
        <param name="srvRecords"><span data-ttu-id="f006c-114">Die Liste der SRV-Einträge in den Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-114">The list of SRV records in the record set.</span></span></param>
        <param name="txtRecords"><span data-ttu-id="f006c-115">Die Liste der TXT-Einträgen in den Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-115">The list of TXT records in the record set.</span></span></param>
        <param name="cnameRecord"><span data-ttu-id="f006c-116">Der CNAME-Eintrag im Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-116">The CNAME record in the  record set.</span></span></param>
        <param name="soaRecord"><span data-ttu-id="f006c-117">Der SOA-Datensatz im Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-117">The SOA record in the record set.</span></span></param>
        <summary>
            <span data-ttu-id="f006c-118">Initialisiert eine neue Instanz der RecordSetInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f006c-118">Initializes a new instance of the RecordSetInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AaaaRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; AaaaRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; AaaaRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.AaaaRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property AaaaRecords As IList(Of AaaaRecord)" />
      <MemberSignature Language="F#" Value="member this.AaaaRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.AaaaRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.AAAARecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-119">Ruft ab oder legt die Liste der AAAA-Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-119">Gets or sets the list of AAAA records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ARecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; ARecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; ARecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.ARecords" />
      <MemberSignature Language="VB.NET" Value="Public Property ARecords As IList(Of ARecord)" />
      <MemberSignature Language="F#" Value="member this.ARecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.ARecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ARecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-120">Ruft ab oder legt die Liste der A-Ressourceneinträge im Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-120">Gets or sets the list of A records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CnameRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord CnameRecord { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord CnameRecord" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.CnameRecord" />
      <MemberSignature Language="VB.NET" Value="Public Property CnameRecord As CnameRecord" />
      <MemberSignature Language="F#" Value="member this.CnameRecord : Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.CnameRecord" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.CNAMERecord")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-121">Ruft ab oder legt den CNAME-Eintrag im Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-121">Gets or sets the CNAME record in the  record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f006c-122">Ruft ab oder legt das Etag der Datensatzgruppe fest.</span><span class="sxs-lookup"><span data-stu-id="f006c-122">Gets or sets the etag of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-123">Ruft ab oder legt die ID der Datensatzgruppe fest.</span><span class="sxs-lookup"><span data-stu-id="f006c-123">Gets or sets the ID of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-124">Ruft ab oder legt die Metadaten, die an die Datensatzgruppe angefügt.</span><span class="sxs-lookup"><span data-stu-id="f006c-124">Gets or sets the metadata attached to the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MxRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; MxRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; MxRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.MxRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property MxRecords As IList(Of MxRecord)" />
      <MemberSignature Language="F#" Value="member this.MxRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.MxRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.MXRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-125">Ruft ab oder legt die Liste der MX-Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-125">Gets or sets the list of MX records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-126">Ruft ab oder legt den Namen der Datensatzgruppe fest.</span><span class="sxs-lookup"><span data-stu-id="f006c-126">Gets or sets the name of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NsRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; NsRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; NsRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.NsRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property NsRecords As IList(Of NsRecord)" />
      <MemberSignature Language="F#" Value="member this.NsRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.NsRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.NSRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-127">Ruft ab oder legt die Liste der NS-Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-127">Gets or sets the list of NS records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PtrRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; PtrRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; PtrRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.PtrRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property PtrRecords As IList(Of PtrRecord)" />
      <MemberSignature Language="F#" Value="member this.PtrRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.PtrRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.PTRRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-128">Ruft ab oder legt die Liste der PTR-Einträge im Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-128">Gets or sets the list of PTR records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SoaRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord SoaRecord { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord SoaRecord" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SoaRecord" />
      <MemberSignature Language="VB.NET" Value="Public Property SoaRecord As SoaRecord" />
      <MemberSignature Language="F#" Value="member this.SoaRecord : Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SoaRecord" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.SOARecord")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-129">Ruft ab oder legt den SOA-Datensatz im Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="f006c-129">Gets or sets the SOA record in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SrvRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; SrvRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; SrvRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SrvRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property SrvRecords As IList(Of SrvRecord)" />
      <MemberSignature Language="F#" Value="member this.SrvRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SrvRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.SRVRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-130">Ruft ab oder legt die Liste der SRV-Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-130">Gets or sets the list of SRV records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TTL">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TTL { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TTL" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TTL" />
      <MemberSignature Language="VB.NET" Value="Public Property TTL As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TTL : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TTL" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.TTL")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-131">Ruft ab oder legt ihn fest die Gültigkeitsdauer (Time-to-live) der Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-131">Gets or sets the TTL (time-to-live) of the records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TxtRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; TxtRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; TxtRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TxtRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property TxtRecords As IList(Of TxtRecord)" />
      <MemberSignature Language="F#" Value="member this.TxtRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TxtRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.TXTRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-132">Ruft ab oder legt die Liste der TXT-Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="f006c-132">Gets or sets the list of TXT records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f006c-133">Ruft ab oder legt den Typ der Datensatzgruppe fest.</span><span class="sxs-lookup"><span data-stu-id="f006c-133">Gets or sets the type of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>