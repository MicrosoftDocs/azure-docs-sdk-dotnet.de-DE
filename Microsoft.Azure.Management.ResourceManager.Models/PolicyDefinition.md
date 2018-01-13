<Type Name="PolicyDefinition" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition">
  <TypeSignature Language="C#" Value="public class PolicyDefinition : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicyDefinition extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicyDefinition&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type PolicyDefinition = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="47311-101">Die Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="47311-101">The policy definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="47311-102">Initialisiert eine neue Instanz der PolicyDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="47311-102">Initializes a new instance of the PolicyDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyDefinition (string policyType = null, string mode = null, string displayName = null, string description = null, object policyRule = null, object metadata = null, object parameters = null, string id = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string policyType, string mode, string displayName, string description, object policyRule, object metadata, object parameters, string id, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.#ctor(System.String,System.String,System.String,System.String,System.Object,System.Object,System.Object,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional policyType As String = null, Optional mode As String = null, Optional displayName As String = null, Optional description As String = null, Optional policyRule As Object = null, Optional metadata As Object = null, Optional parameters As Object = null, Optional id As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition : string * string * string * string * obj * obj * obj * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition (policyType, mode, displayName, description, policyRule, metadata, parameters, id, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyType" Type="System.String" />
        <Parameter Name="mode" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="policyRule" Type="System.Object" />
        <Parameter Name="metadata" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyType"><span data-ttu-id="47311-103">Der Typ der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="47311-103">The type of policy definition.</span></span> <span data-ttu-id="47311-104">Mögliche Werte sind "NotSpecified", "Vordefiniert" und benutzerdefinierte.</span><span class="sxs-lookup"><span data-stu-id="47311-104">Possible values are NotSpecified, BuiltIn, and Custom.</span></span> <span data-ttu-id="47311-105">Folgende Werte sind möglich: "NotSpecified" "", "Vordefiniert" "", "Custom"</span><span class="sxs-lookup"><span data-stu-id="47311-105">Possible values include: 'NotSpecified', 'BuiltIn', 'Custom'</span></span></param>
        <param name="mode"><span data-ttu-id="47311-106">Die Definition Richtlinienmodus.</span><span class="sxs-lookup"><span data-stu-id="47311-106">The policy definition mode.</span></span> <span data-ttu-id="47311-107">Mögliche Werte sind "NotSpecified", indiziert und allen.</span><span class="sxs-lookup"><span data-stu-id="47311-107">Possible values are NotSpecified, Indexed, and All.</span></span> <span data-ttu-id="47311-108">Folgende Werte sind möglich: "NotSpecified" "", "Indexed", "All"</span><span class="sxs-lookup"><span data-stu-id="47311-108">Possible values include: 'NotSpecified', 'Indexed', 'All'</span></span></param>
        <param name="displayName"><span data-ttu-id="47311-109">Der Anzeigename der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="47311-109">The display name of the policy definition.</span></span></param>
        <param name="description"><span data-ttu-id="47311-110">Die Beschreibung der Gruppenrichtlinien-Definition.</span><span class="sxs-lookup"><span data-stu-id="47311-110">The policy definition description.</span></span></param>
        <param name="policyRule"><span data-ttu-id="47311-111">Die Richtlinienregel.</span><span class="sxs-lookup"><span data-stu-id="47311-111">The policy rule.</span></span></param>
        <param name="metadata"><span data-ttu-id="47311-112">Die Metadaten der Richtlinie Definition.</span><span class="sxs-lookup"><span data-stu-id="47311-112">The policy definition metadata.</span></span></param>
        <param name="parameters"><span data-ttu-id="47311-113">Erforderlich, wenn ein Parameter in der Richtlinienregel verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="47311-113">Required if a parameter is used in policy rule.</span></span></param>
        <param name="id"><span data-ttu-id="47311-114">Die ID der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="47311-114">The ID of the policy definition.</span></span></param>
        <param name="name"><span data-ttu-id="47311-115">Der Name der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="47311-115">The name of the policy definition.</span></span></param>
        <summary>
            <span data-ttu-id="47311-116">Initialisiert eine neue Instanz der PolicyDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="47311-116">Initializes a new instance of the PolicyDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-117">Ruft ab oder legt die Beschreibung der Gruppenrichtlinien-Definition.</span><span class="sxs-lookup"><span data-stu-id="47311-117">Gets or sets the policy definition description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-118">Ruft ab oder legt den Anzeigenamen der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="47311-118">Gets or sets the display name of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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
            <span data-ttu-id="47311-119">Ruft die ID der Richtliniendefinition ab.</span><span class="sxs-lookup"><span data-stu-id="47311-119">Gets the ID of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public object Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As Object" />
      <MemberSignature Language="F#" Value="member this.Metadata : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-120">Ruft ab oder legt die Metadaten der Policy-Definition.</span><span class="sxs-lookup"><span data-stu-id="47311-120">Gets or sets the policy definition metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public string Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As String" />
      <MemberSignature Language="F#" Value="member this.Mode : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-121">Ruft ab oder legt die Definition Richtlinienmodus.</span><span class="sxs-lookup"><span data-stu-id="47311-121">Gets or sets the policy definition mode.</span></span> <span data-ttu-id="47311-122">Mögliche Werte sind "NotSpecified", indiziert und allen.</span><span class="sxs-lookup"><span data-stu-id="47311-122">Possible values are NotSpecified, Indexed, and All.</span></span> <span data-ttu-id="47311-123">Folgende Werte sind möglich: "NotSpecified" "", "Indexed", "All"</span><span class="sxs-lookup"><span data-stu-id="47311-123">Possible values include: 'NotSpecified', 'Indexed', 'All'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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
            <span data-ttu-id="47311-124">Ruft den Namen der Richtliniendefinition ab.</span><span class="sxs-lookup"><span data-stu-id="47311-124">Gets the name of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-125">Ruft ab oder legt erforderlich, wenn ein Parameter in der Richtlinienregel verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="47311-125">Gets or sets required if a parameter is used in policy rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyRule">
      <MemberSignature Language="C#" Value="public object PolicyRule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PolicyRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyRule" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyRule As Object" />
      <MemberSignature Language="F#" Value="member this.PolicyRule : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-126">Ruft ab oder legt die Richtlinienregel.</span><span class="sxs-lookup"><span data-stu-id="47311-126">Gets or sets the policy rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyType">
      <MemberSignature Language="C#" Value="public string PolicyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyType" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyType As String" />
      <MemberSignature Language="F#" Value="member this.PolicyType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47311-127">Ruft ab oder legt den Typ der Richtliniendefinition fest.</span><span class="sxs-lookup"><span data-stu-id="47311-127">Gets or sets the type of policy definition.</span></span> <span data-ttu-id="47311-128">Mögliche Werte sind "NotSpecified", "Vordefiniert" und benutzerdefinierte.</span><span class="sxs-lookup"><span data-stu-id="47311-128">Possible values are NotSpecified, BuiltIn, and Custom.</span></span> <span data-ttu-id="47311-129">Folgende Werte sind möglich: "NotSpecified" "", "Vordefiniert" "", "Custom"</span><span class="sxs-lookup"><span data-stu-id="47311-129">Possible values include: 'NotSpecified', 'BuiltIn', 'Custom'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>