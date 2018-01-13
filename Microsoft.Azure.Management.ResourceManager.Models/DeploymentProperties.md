<Type Name="DeploymentProperties" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties">
  <TypeSignature Language="C#" Value="public class DeploymentProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentProperties" />
  <TypeSignature Language="F#" Value="type DeploymentProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="30293-101">Bereitstellungseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="30293-101">Deployment properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="30293-102">Initialisiert eine neue Instanz der "DeploymentProperties"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30293-102">Initializes a new instance of the DeploymentProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentProperties (Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode mode, object template = null, Microsoft.Azure.Management.ResourceManager.Models.TemplateLink templateLink = null, object parameters = null, Microsoft.Azure.Management.ResourceManager.Models.ParametersLink parametersLink = null, Microsoft.Azure.Management.ResourceManager.Models.DebugSetting debugSetting = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode mode, object template, class Microsoft.Azure.Management.ResourceManager.Models.TemplateLink templateLink, object parameters, class Microsoft.Azure.Management.ResourceManager.Models.ParametersLink parametersLink, class Microsoft.Azure.Management.ResourceManager.Models.DebugSetting debugSetting) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.#ctor(Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode,System.Object,Microsoft.Azure.Management.ResourceManager.Models.TemplateLink,System.Object,Microsoft.Azure.Management.ResourceManager.Models.ParametersLink,Microsoft.Azure.Management.ResourceManager.Models.DebugSetting)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties : Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode * obj * Microsoft.Azure.Management.ResourceManager.Models.TemplateLink * obj * Microsoft.Azure.Management.ResourceManager.Models.ParametersLink * Microsoft.Azure.Management.ResourceManager.Models.DebugSetting -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties (mode, template, templateLink, parameters, parametersLink, debugSetting)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mode" Type="Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode" />
        <Parameter Name="template" Type="System.Object" />
        <Parameter Name="templateLink" Type="Microsoft.Azure.Management.ResourceManager.Models.TemplateLink" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="parametersLink" Type="Microsoft.Azure.Management.ResourceManager.Models.ParametersLink" />
        <Parameter Name="debugSetting" Type="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" />
      </Parameters>
      <Docs>
        <param name="mode"><span data-ttu-id="30293-103">Der Modus, der zum Bereitstellen von Ressourcen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="30293-103">The mode that is used to deploy resources.</span></span> <span data-ttu-id="30293-104">Mögliche Werte sind inkrementell oder vollständig.</span><span class="sxs-lookup"><span data-stu-id="30293-104">This value can be either Incremental or Complete.</span></span> <span data-ttu-id="30293-105">Im inkrementellen Modus werden Ressourcen bereitgestellt, ohne Löschen der vorhandene Ressourcen an, die nicht in der Vorlage enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="30293-105">In Incremental mode, resources are deployed without deleting existing resources that are not included in the template.</span></span> <span data-ttu-id="30293-106">Im vollständigen Modus Ressourcen bereitgestellt werden, und vorhandene Ressourcen in der Ressourcengruppe, die nicht in der Vorlage enthalten sind, werden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="30293-106">In Complete mode, resources are deployed and existing resources in the resource group that are not included in the template are deleted.</span></span> <span data-ttu-id="30293-107">Seien Sie vorsichtig bei Verwendung des vollständigen Modus sobald Ressourcen möglicherweise unbeabsichtigt gelöscht.</span><span class="sxs-lookup"><span data-stu-id="30293-107">Be careful when using Complete mode as you may unintentionally delete resources.</span></span> <span data-ttu-id="30293-108">Folgende Werte sind möglich: "Inkrementell", "Abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="30293-108">Possible values include: 'Incremental', 'Complete'</span></span></param>
        <param name="template"><span data-ttu-id="30293-109">Der Inhalt der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="30293-109">The template content.</span></span> <span data-ttu-id="30293-110">Wenn Sie die Vorlagensyntax direkt in die Anforderung anstelle von Link zu einer vorhandenen Vorlage übergeben möchten, verwenden Sie dieses Element.</span><span class="sxs-lookup"><span data-stu-id="30293-110">You use this element when you want to pass the template syntax directly in the request rather than link to an existing template.</span></span> <span data-ttu-id="30293-111">Es kann eine JObject oder JSON-Zeichenfolge wohlgeformt sein.</span><span class="sxs-lookup"><span data-stu-id="30293-111">It can be a JObject or well-formed JSON string.</span></span> <span data-ttu-id="30293-112">Verwenden Sie das TemplateLink-Eigenschaft oder die Template-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-112">Use either the templateLink property or the template property, but not both.</span></span></param>
        <param name="templateLink"><span data-ttu-id="30293-113">Der URI der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="30293-113">The URI of the template.</span></span> <span data-ttu-id="30293-114">Verwenden Sie das TemplateLink-Eigenschaft oder die Template-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-114">Use either the templateLink property or the template property, but not both.</span></span></param>
        <param name="parameters"><span data-ttu-id="30293-115">Name-Wert-Paare, die die Bereitstellungsparameter für die Vorlage definieren.</span><span class="sxs-lookup"><span data-stu-id="30293-115">Name and value pairs that define the deployment parameters for the template.</span></span> <span data-ttu-id="30293-116">Wenn Sie die Parameterwerte direkt in die Anforderung anstelle von Link zu einer vorhandenen Parameterdatei bereitstellen möchten, verwenden Sie dieses Element.</span><span class="sxs-lookup"><span data-stu-id="30293-116">You use this element when you want to provide the parameter values directly in the request rather than link to an existing parameter file.</span></span> <span data-ttu-id="30293-117">Verwenden Sie das ParametersLink-Eigenschaft oder das Parameters-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-117">Use either the parametersLink property or the parameters property, but not both.</span></span>
            <span data-ttu-id="30293-118">JObject oder einer JSON-Zeichenfolge wohlgeformt sind möglich.</span><span class="sxs-lookup"><span data-stu-id="30293-118">It can be a JObject or a well formed JSON string.</span></span></param>
        <param name="parametersLink"><span data-ttu-id="30293-119">Der URI der Parameterdatei.</span><span class="sxs-lookup"><span data-stu-id="30293-119">The URI of parameters file.</span></span> <span data-ttu-id="30293-120">Verwenden Sie dieses Element an eine vorhandene Parameterdatei verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="30293-120">You use this element to link to an existing parameters file.</span></span> <span data-ttu-id="30293-121">Verwenden Sie das ParametersLink-Eigenschaft oder das Parameters-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-121">Use either the parametersLink property or the parameters property, but not both.</span></span></param>
        <param name="debugSetting"><span data-ttu-id="30293-122">Die Debugeinstellung der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="30293-122">The debug setting of the deployment.</span></span></param>
        <summary>
            <span data-ttu-id="30293-123">Initialisiert eine neue Instanz der "DeploymentProperties"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30293-123">Initializes a new instance of the DeploymentProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DebugSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DebugSetting DebugSetting { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.DebugSetting DebugSetting" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.DebugSetting" />
      <MemberSignature Language="VB.NET" Value="Public Property DebugSetting As DebugSetting" />
      <MemberSignature Language="F#" Value="member this.DebugSetting : Microsoft.Azure.Management.ResourceManager.Models.DebugSetting with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.DebugSetting" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="debugSetting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DebugSetting</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30293-124">Ermittelt oder definiert das Debug-Einstellung der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="30293-124">Gets or sets the debug setting of the deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As DeploymentMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30293-125">Ruft ab oder legt den Modus an, der zum Bereitstellen von Ressourcen verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="30293-125">Gets or sets the mode that is used to deploy resources.</span></span> <span data-ttu-id="30293-126">Mögliche Werte sind inkrementell oder vollständig.</span><span class="sxs-lookup"><span data-stu-id="30293-126">This value can be either Incremental or Complete.</span></span> <span data-ttu-id="30293-127">Im inkrementellen Modus werden Ressourcen bereitgestellt, ohne Löschen der vorhandene Ressourcen an, die nicht in der Vorlage enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="30293-127">In Incremental mode, resources are deployed without deleting existing resources that are not included in the template.</span></span> <span data-ttu-id="30293-128">Im vollständigen Modus Ressourcen bereitgestellt werden, und vorhandene Ressourcen in der Ressourcengruppe, die nicht in der Vorlage enthalten sind, werden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="30293-128">In Complete mode, resources are deployed and existing resources in the resource group that are not included in the template are deleted.</span></span> <span data-ttu-id="30293-129">Seien Sie vorsichtig bei Verwendung des vollständigen Modus sobald Ressourcen möglicherweise unbeabsichtigt gelöscht.</span><span class="sxs-lookup"><span data-stu-id="30293-129">Be careful when using Complete mode as you may unintentionally delete resources.</span></span> <span data-ttu-id="30293-130">Folgende Werte sind möglich: "Inkrementell", "Abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="30293-130">Possible values include: 'Incremental', 'Complete'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="30293-131">Abrufen oder Festlegen von Name-Wert-Paare, die die Bereitstellungsparameter für die Vorlage definieren.</span><span class="sxs-lookup"><span data-stu-id="30293-131">Gets or sets name and value pairs that define the deployment parameters for the template.</span></span> <span data-ttu-id="30293-132">Wenn Sie die Parameterwerte direkt in die Anforderung anstelle von Link zu einer vorhandenen Parameterdatei bereitstellen möchten, verwenden Sie dieses Element.</span><span class="sxs-lookup"><span data-stu-id="30293-132">You use this element when you want to provide the parameter values directly in the request rather than link to an existing parameter file.</span></span> <span data-ttu-id="30293-133">Verwenden Sie das ParametersLink-Eigenschaft oder das Parameters-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-133">Use either the parametersLink property or the parameters property, but not both.</span></span> <span data-ttu-id="30293-134">JObject oder einer JSON-Zeichenfolge wohlgeformt sind möglich.</span><span class="sxs-lookup"><span data-stu-id="30293-134">It can be a JObject or a well formed JSON string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ParametersLink ParametersLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ParametersLink ParametersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.ParametersLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ParametersLink As ParametersLink" />
      <MemberSignature Language="F#" Value="member this.ParametersLink : Microsoft.Azure.Management.ResourceManager.Models.ParametersLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.ParametersLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parametersLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ParametersLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30293-135">Ruft ab oder legt den URI der Parameterdatei.</span><span class="sxs-lookup"><span data-stu-id="30293-135">Gets or sets the URI of parameters file.</span></span> <span data-ttu-id="30293-136">Verwenden Sie dieses Element an eine vorhandene Parameterdatei verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="30293-136">You use this element to link to an existing parameters file.</span></span> <span data-ttu-id="30293-137">Verwenden Sie das ParametersLink-Eigenschaft oder das Parameters-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-137">Use either the parametersLink property or the parameters property, but not both.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public object Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As Object" />
      <MemberSignature Language="F#" Value="member this.Template : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Template" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="30293-138">Ruft ab oder legt den Vorlageninhalt.</span><span class="sxs-lookup"><span data-stu-id="30293-138">Gets or sets the template content.</span></span> <span data-ttu-id="30293-139">Wenn Sie die Vorlagensyntax direkt in die Anforderung anstelle von Link zu einer vorhandenen Vorlage übergeben möchten, verwenden Sie dieses Element.</span><span class="sxs-lookup"><span data-stu-id="30293-139">You use this element when you want to pass the template syntax directly in the request rather than link to an existing template.</span></span> <span data-ttu-id="30293-140">Es kann eine JObject oder JSON-Zeichenfolge wohlgeformt sein.</span><span class="sxs-lookup"><span data-stu-id="30293-140">It can be a JObject or well-formed JSON string.</span></span> <span data-ttu-id="30293-141">Verwenden Sie das TemplateLink-Eigenschaft oder die Template-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-141">Use either the templateLink property or the template property, but not both.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TemplateLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.TemplateLink TemplateLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.TemplateLink TemplateLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.TemplateLink" />
      <MemberSignature Language="VB.NET" Value="Public Property TemplateLink As TemplateLink" />
      <MemberSignature Language="F#" Value="member this.TemplateLink : Microsoft.Azure.Management.ResourceManager.Models.TemplateLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.TemplateLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="templateLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TemplateLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30293-142">Ruft ab oder legt den URI der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="30293-142">Gets or sets the URI of the template.</span></span> <span data-ttu-id="30293-143">Verwenden Sie das TemplateLink-Eigenschaft oder die Template-Eigenschaft jedoch nicht beides.</span><span class="sxs-lookup"><span data-stu-id="30293-143">Use either the templateLink property or the template property, but not both.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentProperties.Validate " />
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
            <span data-ttu-id="30293-144">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="30293-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="30293-145">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="30293-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>