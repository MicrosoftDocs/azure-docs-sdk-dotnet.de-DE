<Type Name="Crs" FullName="Microsoft.Azure.Documents.Spatial.Crs">
  <TypeSignature Language="C#" Value="public abstract class Crs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Crs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Crs" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Crs" />
  <TypeSignature Language="F#" Value="type Crs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.CrsJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3ad42-101">Referenzsystem koordinieren darstellt in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="3ad42-101">Represents Coordinate Reference System in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Crs (Microsoft.Azure.Documents.Spatial.CrsType type);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.Spatial.CrsType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.#ctor(Microsoft.Azure.Documents.Spatial.CrsType)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (type As CrsType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Crs : Microsoft.Azure.Documents.Spatial.CrsType -&gt; Microsoft.Azure.Documents.Spatial.Crs" Usage="new Microsoft.Azure.Documents.Spatial.Crs type" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Documents.Spatial.CrsType" />
      </Parameters>
      <Docs>
        <param name="type">
            <span data-ttu-id="3ad42-102">CR-Typ.</span><span class="sxs-lookup"><span data-stu-id="3ad42-102">CRS type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ad42-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="3ad42-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.Crs Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Documents.Spatial.Crs Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As Crs" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ad42-104">Ruft die standardmäßigen CRS im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="3ad42-104">Gets default CRS in the Azure Cosmos DB service.</span></span> <span data-ttu-id="3ad42-105">Standardmäßige CRS wird CRS mit dem Namen "Urn: Ogc:def:crs:OGC:1.3:CRS84" benannt werden.</span><span class="sxs-lookup"><span data-stu-id="3ad42-105">Default CRS is named CRS with the name "urn:ogc:def:crs:OGC:1.3:CRS84".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linked">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.LinkedCrs Linked (string href);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.LinkedCrs Linked(string href) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Linked(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Linked (href As String) As LinkedCrs" />
      <MemberSignature Language="F#" Value="static member Linked : string -&gt; Microsoft.Azure.Documents.Spatial.LinkedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Linked href" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.LinkedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="href" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="href">
            <span data-ttu-id="3ad42-106">CR-Link.</span><span class="sxs-lookup"><span data-stu-id="3ad42-106">CRS link.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ad42-107">Erstellt verknüpften CRS im Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="3ad42-107">Creates linked CRS in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3ad42-108">Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ad42-108">Instance of <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> class.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linked">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.LinkedCrs Linked (string href, string type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.LinkedCrs Linked(string href, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Linked(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Linked (href As String, type As String) As LinkedCrs" />
      <MemberSignature Language="F#" Value="static member Linked : string * string -&gt; Microsoft.Azure.Documents.Spatial.LinkedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Linked (href, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.LinkedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="href">
            <span data-ttu-id="3ad42-109">CR-Link.</span><span class="sxs-lookup"><span data-stu-id="3ad42-109">CRS link.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="3ad42-110">CRS Linktyp.</span><span class="sxs-lookup"><span data-stu-id="3ad42-110">CRS link type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ad42-111">Verknüpfte CRS erstellt mit optional in der Azure-Cosmos-DB-Dienst angegebenen Typs.</span><span class="sxs-lookup"><span data-stu-id="3ad42-111">Creates linked CRS with the optional type specified in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3ad42-112">Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ad42-112">Instance of <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> class.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Named">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.NamedCrs Named (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.NamedCrs Named(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Named(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Named (name As String) As NamedCrs" />
      <MemberSignature Language="F#" Value="static member Named : string -&gt; Microsoft.Azure.Documents.Spatial.NamedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Named name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.NamedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3ad42-113">CR-Name.</span><span class="sxs-lookup"><span data-stu-id="3ad42-113">CRS name.</span></span></param>
        <summary>
            <span data-ttu-id="3ad42-114">Erstellt benannte CRS mit dem Namen in der Azure-Cosmos-DB-Dienst angegeben.</span><span class="sxs-lookup"><span data-stu-id="3ad42-114">Creates named CRS with the name specified in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="3ad42-115">Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ad42-115">Instance of <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> class.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.CrsType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.Spatial.CrsType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As CrsType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Documents.Spatial.CrsType" Usage="Microsoft.Azure.Documents.Spatial.Crs.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.CrsType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ad42-116">Ruft den CRS-Typ in der Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="3ad42-116">Gets CRS type in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="3ad42-117">Typ des CRS.</span><span class="sxs-lookup"><span data-stu-id="3ad42-117">Type of CRS.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unspecified">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.Crs Unspecified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Documents.Spatial.Crs Unspecified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Unspecified" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unspecified As Crs" />
      <MemberSignature Language="F#" Value="member this.Unspecified : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Unspecified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ad42-118">Ruft "Nicht angegeben" CR im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="3ad42-118">Gets "Unspecified" CRS in the Azure Cosmos DB service.</span></span> <span data-ttu-id="3ad42-119">Keine CRS können für Geometrien müssen "nicht angegeben" CR davon ausgegangen werden.</span><span class="sxs-lookup"><span data-stu-id="3ad42-119">No CRS can be assumed for Geometries having "Unspecified" CRS.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>