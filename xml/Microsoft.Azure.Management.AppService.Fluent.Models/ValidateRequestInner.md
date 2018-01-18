<Type Name="ValidateRequestInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner">
  <TypeSignature Language="C#" Value="public class ValidateRequestInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateRequestInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateRequestInner" />
  <TypeSignature Language="F#" Value="type ValidateRequestInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66936-101">Anforderungsinhalt Ressource-Validierung.</span><span class="sxs-lookup"><span data-stu-id="66936-101">Resource validation request content.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateRequestInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66936-102">Initialisiert eine neue Instanz der ValidateRequestInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="66936-102">Initializes a new instance of the ValidateRequestInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateRequestInner (string name, string type, string location, string serverFarmId = null, string skuName = null, Nullable&lt;bool&gt; needLinuxWorkers = null, Nullable&lt;int&gt; capacity = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, string location, string serverFarmId, string skuName, valuetype System.Nullable`1&lt;bool&gt; needLinuxWorkers, valuetype System.Nullable`1&lt;int32&gt; capacity, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As String, location As String, Optional serverFarmId As String = null, Optional skuName As String = null, Optional needLinuxWorkers As Nullable(Of Boolean) = null, Optional capacity As Nullable(Of Integer) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner : string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner (name, type, location, serverFarmId, skuName, needLinuxWorkers, capacity, hostingEnvironment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="skuName" Type="System.String" />
        <Parameter Name="needLinuxWorkers" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="66936-103">Der Ressourcenname überprüfen.</span><span class="sxs-lookup"><span data-stu-id="66936-103">Resource name to verify.</span></span></param>
        <param name="type"><span data-ttu-id="66936-104">Ressourcentyp zur Überprüfung verwendet.</span><span class="sxs-lookup"><span data-stu-id="66936-104">Resource type used for verification.</span></span> <span data-ttu-id="66936-105">Folgende Werte sind möglich: "Serverfarm"","Standort"</span><span class="sxs-lookup"><span data-stu-id="66936-105">Possible values include: 'ServerFarm', 'Site'</span></span></param>
        <param name="location"><span data-ttu-id="66936-106">Erwarteten Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="66936-106">Expected location of the resource.</span></span></param>
        <param name="serverFarmId"><span data-ttu-id="66936-107">ARM-Ressourcen-ID der App Service-Plan, der die app hosten möchten.</span><span class="sxs-lookup"><span data-stu-id="66936-107">ARM resource ID of an App Service plan that would host the app.</span></span></param>
        <param name="skuName"><span data-ttu-id="66936-108">Name des Ziel-SKU für den App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="66936-108">Name of the target SKU for the App Service plan.</span></span></param>
        <param name="needLinuxWorkers"><span data-ttu-id="66936-109">&lt;Code&gt;"true"&lt;/code&gt; App Service-Plan ist für Linux-Worker; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="66936-109">&lt;code&gt;true&lt;/code&gt; if App Service plan is for Linux workers; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="capacity"><span data-ttu-id="66936-110">Kapazität des App Service-Plan (Anzahl der virtuellen Maschine) als Ziel verwenden.</span><span class="sxs-lookup"><span data-stu-id="66936-110">Target capacity of the App Service plan (number of VM's).</span></span></param>
        <param name="hostingEnvironment"><span data-ttu-id="66936-111">Name des App Service-Umgebung, in dem app oder die App Service-Plan erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="66936-111">Name of App Service Environment where app or App Service plan should be created.</span></span></param>
        <summary>
            <span data-ttu-id="66936-112">Initialisiert eine neue Instanz der ValidateRequestInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="66936-112">Initializes a new instance of the ValidateRequestInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66936-113">Ruft ab, oder legt ihn fest Ziel Kapazität von der App Service-Plan (Anzahl der virtuellen Maschine).</span><span class="sxs-lookup"><span data-stu-id="66936-113">Gets or sets target capacity of the App Service plan (number of VM's).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66936-114">Ruft ab oder legt die Namen der App Service-Umgebung, in dem app oder die App Service-Plan erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="66936-114">Gets or sets name of App Service Environment where app or App Service plan should be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66936-115">Ruft ab, oder legt ihn fest erwarteten Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="66936-115">Gets or sets expected location of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66936-116">Ruft ab, oder legt ihn fest Ressourcennamen, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="66936-116">Gets or sets resource name to verify.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NeedLinuxWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NeedLinuxWorkers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NeedLinuxWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.NeedLinuxWorkers" />
      <MemberSignature Language="VB.NET" Value="Public Property NeedLinuxWorkers As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NeedLinuxWorkers : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.NeedLinuxWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.needLinuxWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66936-117">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; App Service-Plan ist für Linux-Worker; andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt ;.</span><span class="sxs-lookup"><span data-stu-id="66936-117">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if App Service plan is for Linux workers; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66936-118">Ruft ab, oder legt ihn fest ARM-Ressourcen-ID der App Service-Plan, der die app hosten möchten.</span><span class="sxs-lookup"><span data-stu-id="66936-118">Gets or sets ARM resource ID of an App Service plan that would host the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkuName">
      <MemberSignature Language="C#" Value="public string SkuName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SkuName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.SkuName" />
      <MemberSignature Language="VB.NET" Value="Public Property SkuName As String" />
      <MemberSignature Language="F#" Value="member this.SkuName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.SkuName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.skuName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66936-119">Ruft ab oder legt den Namen des Ziel-SKU für den App Service-Plan fest.</span><span class="sxs-lookup"><span data-stu-id="66936-119">Gets or sets name of the target SKU for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66936-120">Ruft ab, oder legt ihn fest Ressourcentyp zur Überprüfung verwendet.</span><span class="sxs-lookup"><span data-stu-id="66936-120">Gets or sets resource type used for verification.</span></span> <span data-ttu-id="66936-121">Folgende Werte sind möglich: "Serverfarm"","Standort"</span><span class="sxs-lookup"><span data-stu-id="66936-121">Possible values include: 'ServerFarm', 'Site'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateRequestInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="validateRequestInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66936-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="66936-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="66936-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="66936-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>