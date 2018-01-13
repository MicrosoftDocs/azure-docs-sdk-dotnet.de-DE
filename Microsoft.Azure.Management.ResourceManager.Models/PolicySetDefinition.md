<Type Name="PolicySetDefinition" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition">
  <TypeSignature Language="C#" Value="public class PolicySetDefinition : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicySetDefinition extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicySetDefinition&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type PolicySetDefinition = class&#xA;    interface IResource" />
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
            <span data-ttu-id="14083-101">Die Richtlinie festgelegt Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-101">The policy set definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicySetDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14083-102">Initialisiert eine neue Instanz der PolicySetDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14083-102">Initializes a new instance of the PolicySetDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicySetDefinition (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; policyDefinitions, string policyType = null, string displayName = null, string description = null, object metadata = null, object parameters = null, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; policyDefinitions, string policyType, string displayName, string description, object metadata, object parameters, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference},System.String,System.String,System.String,System.Object,System.Object,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (policyDefinitions As IList(Of PolicyDefinitionReference), Optional policyType As String = null, Optional displayName As String = null, Optional description As String = null, Optional metadata As Object = null, Optional parameters As Object = null, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; * string * string * string * obj * obj * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition (policyDefinitions, policyType, displayName, description, metadata, parameters, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyDefinitions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt;" />
        <Parameter Name="policyType" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="metadata" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyDefinitions"><span data-ttu-id="14083-103">Ein Array von Definition verweisen.</span><span class="sxs-lookup"><span data-stu-id="14083-103">An array of policy definition references.</span></span></param>
        <param name="policyType"><span data-ttu-id="14083-104">Der Typ der Richtliniendefinition.</span><span class="sxs-lookup"><span data-stu-id="14083-104">The type of policy definition.</span></span> <span data-ttu-id="14083-105">Mögliche Werte sind "NotSpecified", "Vordefiniert" und benutzerdefinierte.</span><span class="sxs-lookup"><span data-stu-id="14083-105">Possible values are NotSpecified, BuiltIn, and Custom.</span></span> <span data-ttu-id="14083-106">Folgende Werte sind möglich: "NotSpecified" "", "Vordefiniert" "", "Custom"</span><span class="sxs-lookup"><span data-stu-id="14083-106">Possible values include: 'NotSpecified', 'BuiltIn', 'Custom'</span></span></param>
        <param name="displayName"><span data-ttu-id="14083-107">Der Anzeigename der Richtlinie festgelegt Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-107">The display name of the policy set definition.</span></span></param>
        <param name="description"><span data-ttu-id="14083-108">Die Richtlinie festgelegt definitionsbeschreibung.</span><span class="sxs-lookup"><span data-stu-id="14083-108">The policy set definition description.</span></span></param>
        <param name="metadata"><span data-ttu-id="14083-109">Die Richtlinie festgelegt, die Metadaten-Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-109">The policy set definition metadata.</span></span></param>
        <param name="parameters"><span data-ttu-id="14083-110">Die Richtlinie festgelegt Definition-Parameter, die verwendet werden können, in der Definition verweisen.</span><span class="sxs-lookup"><span data-stu-id="14083-110">The policy set definition parameters that can be used in policy definition references.</span></span></param>
        <param name="id"><span data-ttu-id="14083-111">Die ID der Richtlinie festgelegt Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-111">The ID of the policy set definition.</span></span></param>
        <param name="name"><span data-ttu-id="14083-112">Der Name der Richtlinie festgelegt Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-112">The name of the policy set definition.</span></span></param>
        <param name="type"><span data-ttu-id="14083-113">Der Typ der Ressource (Microsoft.Authorization/policySetDefinitions).</span><span class="sxs-lookup"><span data-stu-id="14083-113">The type of the resource (Microsoft.Authorization/policySetDefinitions).</span></span></param>
        <summary>
            <span data-ttu-id="14083-114">Initialisiert eine neue Instanz der PolicySetDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14083-114">Initializes a new instance of the PolicySetDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Description" />
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
            <span data-ttu-id="14083-115">Abrufen oder Festlegen der Richtlinie Satz definitionsbeschreibung.</span><span class="sxs-lookup"><span data-stu-id="14083-115">Gets or sets the policy set definition description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.DisplayName" />
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
            <span data-ttu-id="14083-116">Ruft ab oder legt sie fest der Anzeigenamen der Richtlinie Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-116">Gets or sets the display name of the policy set definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Id" />
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
            <span data-ttu-id="14083-117">Ruft die ID der Definition der Richtlinie ab.</span><span class="sxs-lookup"><span data-stu-id="14083-117">Gets the ID of the policy set definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public object Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As Object" />
      <MemberSignature Language="F#" Value="member this.Metadata : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Metadata" />
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
            <span data-ttu-id="14083-118">Abrufen oder Festlegen der Metadaten der Richtlinie Set-Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-118">Gets or sets the policy set definition metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Name" />
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
            <span data-ttu-id="14083-119">Ruft der Namen der Richtlinie festgelegten Definition.</span><span class="sxs-lookup"><span data-stu-id="14083-119">Gets the name of the policy set definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Parameters" />
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
            <span data-ttu-id="14083-120">Im abruft oder festlegt Satz Definition Richtlinienparameter, die verwendet werden können Definition verweisen.</span><span class="sxs-lookup"><span data-stu-id="14083-120">Gets or sets the policy set definition parameters that can be used in policy definition references.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyDefinitions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; PolicyDefinitions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; PolicyDefinitions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyDefinitions" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyDefinitions As IList(Of PolicyDefinitionReference)" />
      <MemberSignature Language="F#" Value="member this.PolicyDefinitions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyDefinitions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyDefinitions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14083-121">Ruft ab oder legt ein Array von Definition verweisen.</span><span class="sxs-lookup"><span data-stu-id="14083-121">Gets or sets an array of policy definition references.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyType">
      <MemberSignature Language="C#" Value="public string PolicyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyType" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyType As String" />
      <MemberSignature Language="F#" Value="member this.PolicyType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyType" />
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
            <span data-ttu-id="14083-122">Ruft ab oder legt den Typ der Richtliniendefinition fest.</span><span class="sxs-lookup"><span data-stu-id="14083-122">Gets or sets the type of policy definition.</span></span> <span data-ttu-id="14083-123">Mögliche Werte sind "NotSpecified", "Vordefiniert" und benutzerdefinierte.</span><span class="sxs-lookup"><span data-stu-id="14083-123">Possible values are NotSpecified, BuiltIn, and Custom.</span></span> <span data-ttu-id="14083-124">Folgende Werte sind möglich: "NotSpecified" "", "Vordefiniert" "", "Custom"</span><span class="sxs-lookup"><span data-stu-id="14083-124">Possible values include: 'NotSpecified', 'BuiltIn', 'Custom'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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
            <span data-ttu-id="14083-125">Ruft den Typ der Ressource (Microsoft.Authorization/policySetDefinitions) ab.</span><span class="sxs-lookup"><span data-stu-id="14083-125">Gets the type of the resource (Microsoft.Authorization/policySetDefinitions).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="policySetDefinition.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14083-126">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="14083-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="14083-127">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="14083-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>