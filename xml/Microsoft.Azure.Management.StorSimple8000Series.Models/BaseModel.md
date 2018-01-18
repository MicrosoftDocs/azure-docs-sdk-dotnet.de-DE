<Type Name="BaseModel" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel">
  <TypeSignature Language="C#" Value="public class BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BaseModel extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="VB.NET" Value="Public Class BaseModel" />
  <TypeSignature Language="F#" Value="type BaseModel = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9f0e-101">Stellt die Basisklasse für alle anderen ARM-Objektmodelle</span><span class="sxs-lookup"><span data-stu-id="c9f0e-101">Represents the base class for all other ARM object models</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaseModel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9f0e-102">Initialisiert eine neue Instanz der BaseModel-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-102">Initializes a new instance of the BaseModel class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaseModel (string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel : string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel (id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c9f0e-103">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-103">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="c9f0e-104">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-104">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="c9f0e-105">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-105">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="c9f0e-106">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-106">The Kind of the object.</span></span> <span data-ttu-id="c9f0e-107">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-107">Currently only Series8000 is supported.</span></span> <span data-ttu-id="c9f0e-108">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="c9f0e-108">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="c9f0e-109">Initialisiert eine neue Instanz der BaseModel-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-109">Initializes a new instance of the BaseModel class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c9f0e-110">Ruft die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-110">Gets the path ID that uniquely identifies the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9f0e-111">Ruft ab oder legt die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-111">Gets or sets the Kind of the object.</span></span> <span data-ttu-id="c9f0e-112">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-112">Currently only Series8000 is supported.</span></span> <span data-ttu-id="c9f0e-113">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="c9f0e-113">Possible values include: 'Series8000'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c9f0e-114">Ruft den Namen des Objekts ab.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-114">Gets the name of the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c9f0e-115">Ruft den hierarchischen Typ des Objekts ab.</span><span class="sxs-lookup"><span data-stu-id="c9f0e-115">Gets the hierarchical type of the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>