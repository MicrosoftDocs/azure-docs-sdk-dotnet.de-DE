<Type Name="DeploymentProperties" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties">
  <TypeSignature Language="C#" Value="public class DeploymentProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentProperties" />
  <TypeSignature Language="F#" Value="type DeploymentProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc7b0-101">Bereitstellungseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-101">Deployment properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-102">Initialisiert eine neue Instanz der "DeploymentProperties"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-102">Initializes a new instance of the DeploymentProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentProperties (Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode mode, object template = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink templateLink = null, object parameters = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink parametersLink = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting debugSetting = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode mode, object template, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink templateLink, object parameters, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink parametersLink, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting debugSetting) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode,System.Object,Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink,System.Object,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties : Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode * obj * Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink * obj * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties (mode, template, templateLink, parameters, parametersLink, debugSetting)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mode" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode" />
        <Parameter Name="template" Type="System.Object" />
        <Parameter Name="templateLink" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="parametersLink" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink" />
        <Parameter Name="debugSetting" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting" />
      </Parameters>
      <Docs>
        <param name="mode"><span data-ttu-id="dc7b0-103">Der Bereitstellungsmodus.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-103">The deployment mode.</span></span> <span data-ttu-id="dc7b0-104">Folgende Werte sind möglich: "Inkrementell", "Abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="dc7b0-104">Possible values include: 'Incremental', 'Complete'</span></span></param>
        <param name="template"><span data-ttu-id="dc7b0-105">Der Inhalt der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-105">The template content.</span></span> <span data-ttu-id="dc7b0-106">JObject oder einer JSON-Zeichenfolge wohlgeformt sind möglich.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-106">It can be a JObject or a well formed JSON string.</span></span> <span data-ttu-id="dc7b0-107">Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-107">Use only one of Template or TemplateLink.</span></span></param>
        <param name="templateLink"><span data-ttu-id="dc7b0-108">Die URI-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-108">The template URI.</span></span> <span data-ttu-id="dc7b0-109">Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-109">Use only one of Template or TemplateLink.</span></span></param>
        <param name="parameters"><span data-ttu-id="dc7b0-110">Deployment-Parameter.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-110">Deployment parameters.</span></span> <span data-ttu-id="dc7b0-111">JObject oder einer JSON-Zeichenfolge wohlgeformt sind möglich.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-111">It can be a JObject or a well formed JSON string.</span></span> <span data-ttu-id="dc7b0-112">Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-112">Use only one of Parameters or ParametersLink.</span></span></param>
        <param name="parametersLink"><span data-ttu-id="dc7b0-113">Die URI-Parameter.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-113">The parameters URI.</span></span> <span data-ttu-id="dc7b0-114">Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-114">Use only one of Parameters or ParametersLink.</span></span></param>
        <param name="debugSetting"><span data-ttu-id="dc7b0-115">Die Debugeinstellung der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-115">The debug setting of the deployment.</span></span></param>
        <summary>
            <span data-ttu-id="dc7b0-116">Initialisiert eine neue Instanz der "DeploymentProperties"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-116">Initializes a new instance of the DeploymentProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DebugSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting DebugSetting { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting DebugSetting" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.DebugSetting" />
      <MemberSignature Language="VB.NET" Value="Public Property DebugSetting As DebugSetting" />
      <MemberSignature Language="F#" Value="member this.DebugSetting : Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.DebugSetting" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="debugSetting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.DebugSetting</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-117">Ermittelt oder definiert das Debug-Einstellung der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-117">Gets or sets the debug setting of the deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As DeploymentMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-118">Ruft ab oder legt den Bereitstellungsmodus.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-118">Gets or sets the deployment mode.</span></span> <span data-ttu-id="dc7b0-119">Folgende Werte sind möglich: "Inkrementell", "Abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="dc7b0-119">Possible values include: 'Incremental', 'Complete'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-120">Ruft ab oder legt die Bereitstellungsparameter.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-120">Gets or sets deployment parameters.</span></span> <span data-ttu-id="dc7b0-121">JObject oder einer JSON-Zeichenfolge wohlgeformt sind möglich.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-121">It can be a JObject or a well formed JSON string.</span></span> <span data-ttu-id="dc7b0-122">Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-122">Use only one of Parameters or ParametersLink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink ParametersLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink ParametersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.ParametersLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ParametersLink As ParametersLink" />
      <MemberSignature Language="F#" Value="member this.ParametersLink : Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.ParametersLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parametersLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.ParametersLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-123">Ruft ab oder legt den URI-Parameter fest.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-123">Gets or sets the parameters URI.</span></span> <span data-ttu-id="dc7b0-124">Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-124">Use only one of Parameters or ParametersLink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public object Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As Object" />
      <MemberSignature Language="F#" Value="member this.Template : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Template" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="template")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-125">Ruft ab oder legt den Vorlageninhalt.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-125">Gets or sets the template content.</span></span> <span data-ttu-id="dc7b0-126">JObject oder einer JSON-Zeichenfolge wohlgeformt sind möglich.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-126">It can be a JObject or a well formed JSON string.</span></span> <span data-ttu-id="dc7b0-127">Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-127">Use only one of Template or TemplateLink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TemplateLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink TemplateLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink TemplateLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.TemplateLink" />
      <MemberSignature Language="VB.NET" Value="Public Property TemplateLink As TemplateLink" />
      <MemberSignature Language="F#" Value="member this.TemplateLink : Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.TemplateLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="templateLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.TemplateLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-128">Ruft ab oder legt die URI-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-128">Gets or sets the template URI.</span></span> <span data-ttu-id="dc7b0-129">Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-129">Use only one of Template or TemplateLink.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc7b0-130">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dc7b0-130">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dc7b0-131">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dc7b0-131">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>