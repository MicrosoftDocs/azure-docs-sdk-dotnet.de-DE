<Type Name="ProcessModuleInfo" FullName="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo">
  <TypeSignature Language="C#" Value="public class ProcessModuleInfo : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProcessModuleInfo extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ProcessModuleInfo&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ProcessModuleInfo = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fe836-101">Modulinformationen verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="fe836-101">Process Module Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProcessModuleInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe836-102">Initialisiert eine neue Instanz der ProcessModuleInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fe836-102">Initializes a new instance of the ProcessModuleInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProcessModuleInfo (string id = null, string name = null, string kind = null, string type = null, string baseAddress = null, string fileName = null, string href = null, string filePath = null, Nullable&lt;int&gt; moduleMemorySize = null, string fileVersion = null, string fileDescription = null, string product = null, string productVersion = null, Nullable&lt;bool&gt; isDebug = null, string language = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string baseAddress, string fileName, string href, string filePath, valuetype System.Nullable`1&lt;int32&gt; moduleMemorySize, string fileVersion, string fileDescription, string product, string productVersion, valuetype System.Nullable`1&lt;bool&gt; isDebug, string language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional baseAddress As String = null, Optional fileName As String = null, Optional href As String = null, Optional filePath As String = null, Optional moduleMemorySize As Nullable(Of Integer) = null, Optional fileVersion As String = null, Optional fileDescription As String = null, Optional product As String = null, Optional productVersion As String = null, Optional isDebug As Nullable(Of Boolean) = null, Optional language As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo : string * string * string * string * string * string * string * string * Nullable&lt;int&gt; * string * string * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo (id, name, kind, type, baseAddress, fileName, href, filePath, moduleMemorySize, fileVersion, fileDescription, product, productVersion, isDebug, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="baseAddress" Type="System.String" />
        <Parameter Name="fileName" Type="System.String" />
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="moduleMemorySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="fileVersion" Type="System.String" />
        <Parameter Name="fileDescription" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="productVersion" Type="System.String" />
        <Parameter Name="isDebug" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="language" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="fe836-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="fe836-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="fe836-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="fe836-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="fe836-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe836-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="fe836-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="fe836-106">Resource type.</span></span></param>
        <param name="baseAddress"><span data-ttu-id="fe836-107">Die Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="fe836-107">Base address.</span></span> <span data-ttu-id="fe836-108">Als Modul-ID in der ARM-Ressourcen-URI verwendet.</span><span class="sxs-lookup"><span data-stu-id="fe836-108">Used as module identifier in ARM resource URI.</span></span></param>
        <param name="fileName"><span data-ttu-id="fe836-109">Dateiname</span><span class="sxs-lookup"><span data-stu-id="fe836-109">File name.</span></span></param>
        <param name="href"><span data-ttu-id="fe836-110">HRef-URI.</span><span class="sxs-lookup"><span data-stu-id="fe836-110">HRef URI.</span></span></param>
        <param name="filePath"><span data-ttu-id="fe836-111">Pfad der Datei.</span><span class="sxs-lookup"><span data-stu-id="fe836-111">File path.</span></span></param>
        <param name="moduleMemorySize"><span data-ttu-id="fe836-112">Modulgröße-Speicher.</span><span class="sxs-lookup"><span data-stu-id="fe836-112">Module memory size.</span></span></param>
        <param name="fileVersion"><span data-ttu-id="fe836-113">Dateiversion.</span><span class="sxs-lookup"><span data-stu-id="fe836-113">File version.</span></span></param>
        <param name="fileDescription"><span data-ttu-id="fe836-114">Beschreibung der Datei.</span><span class="sxs-lookup"><span data-stu-id="fe836-114">File description.</span></span></param>
        <param name="product"><span data-ttu-id="fe836-115">Produktname.</span><span class="sxs-lookup"><span data-stu-id="fe836-115">Product name.</span></span></param>
        <param name="productVersion"><span data-ttu-id="fe836-116">Produktversion.</span><span class="sxs-lookup"><span data-stu-id="fe836-116">Product version.</span></span></param>
        <param name="isDebug"><span data-ttu-id="fe836-117">Ist Debug?</span><span class="sxs-lookup"><span data-stu-id="fe836-117">Is debug?</span></span></param>
        <param name="language"><span data-ttu-id="fe836-118">Modul-Sprache (Gebietsschema).</span><span class="sxs-lookup"><span data-stu-id="fe836-118">Module language (locale).</span></span></param>
        <summary>
            <span data-ttu-id="fe836-119">Initialisiert eine neue Instanz der ProcessModuleInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fe836-119">Initializes a new instance of the ProcessModuleInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseAddress">
      <MemberSignature Language="C#" Value="public string BaseAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaseAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.BaseAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseAddress As String" />
      <MemberSignature Language="F#" Value="member this.BaseAddress : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.BaseAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.baseAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-120">Ruft ab, oder legt ihn fest-Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="fe836-120">Gets or sets base address.</span></span> <span data-ttu-id="fe836-121">Als Modul-ID in der ARM-Ressourcen-URI verwendet.</span><span class="sxs-lookup"><span data-stu-id="fe836-121">Used as module identifier in ARM resource URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileDescription">
      <MemberSignature Language="C#" Value="public string FileDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FileDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property FileDescription As String" />
      <MemberSignature Language="F#" Value="member this.FileDescription : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FileDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fileDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-122">Ruft ab oder legt die Beschreibung der Datei.</span><span class="sxs-lookup"><span data-stu-id="fe836-122">Gets or sets file description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public string FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As String" />
      <MemberSignature Language="F#" Value="member this.FileName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fileName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-123">Ruft ab oder legt den Namen fest.</span><span class="sxs-lookup"><span data-stu-id="fe836-123">Gets or sets file name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-124">Ruft ab oder legt der Pfad der Datei.</span><span class="sxs-lookup"><span data-stu-id="fe836-124">Gets or sets file path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileVersion">
      <MemberSignature Language="C#" Value="public string FileVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FileVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property FileVersion As String" />
      <MemberSignature Language="F#" Value="member this.FileVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.FileVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fileVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-125">Ruft ab oder legt die Version der Datei.</span><span class="sxs-lookup"><span data-stu-id="fe836-125">Gets or sets file version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Href">
      <MemberSignature Language="C#" Value="public string Href { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Href" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.Href" />
      <MemberSignature Language="VB.NET" Value="Public Property Href As String" />
      <MemberSignature Language="F#" Value="member this.Href : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.Href" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.href")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-126">Ruft ab, oder legt ihn fest hRef URI.</span><span class="sxs-lookup"><span data-stu-id="fe836-126">Gets or sets hRef URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDebug">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDebug { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDebug" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.IsDebug" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDebug As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDebug : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.IsDebug" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDebug")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-127">Ruft ab oder legt ihn fest ist Debug?</span><span class="sxs-lookup"><span data-stu-id="fe836-127">Gets or sets is debug?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public string Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As String" />
      <MemberSignature Language="F#" Value="member this.Language : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.Language" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.language")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-128">Abrufen oder Festlegen der Modul-Sprache (Gebietsschema).</span><span class="sxs-lookup"><span data-stu-id="fe836-128">Gets or sets module language (locale).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModuleMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ModuleMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ModuleMemorySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.ModuleMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property ModuleMemorySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ModuleMemorySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.ModuleMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.moduleMemorySize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-129">Ruft ab, oder legt ihn fest Modulgröße-Speicher.</span><span class="sxs-lookup"><span data-stu-id="fe836-129">Gets or sets module memory size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.Product" />
      <MemberSignature Language="VB.NET" Value="Public Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.Product" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.product")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-130">Ruft ab, oder legt ihn fest Produktname.</span><span class="sxs-lookup"><span data-stu-id="fe836-130">Gets or sets product name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductVersion">
      <MemberSignature Language="C#" Value="public string ProductVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProductVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.ProductVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ProductVersion As String" />
      <MemberSignature Language="F#" Value="member this.ProductVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo.ProductVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.productVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe836-131">Ruft ab oder legt die Version des Produkts.</span><span class="sxs-lookup"><span data-stu-id="fe836-131">Gets or sets product version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>