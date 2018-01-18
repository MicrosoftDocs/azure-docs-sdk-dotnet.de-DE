<Type Name="ExportTemplateRequestInner" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner">
  <TypeSignature Language="C#" Value="public class ExportTemplateRequestInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportTemplateRequestInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportTemplateRequestInner" />
  <TypeSignature Language="F#" Value="type ExportTemplateRequestInner = class" />
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
            <span data-ttu-id="2a536-101">Exportieren Sie die Gruppe Anforderung ressourcenvorlagenparameter.</span><span class="sxs-lookup"><span data-stu-id="2a536-101">Export resource group template request parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportTemplateRequestInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a536-102">Initialisiert eine neue Instanz der ExportTemplateRequestInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2a536-102">Initializes a new instance of the ExportTemplateRequestInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportTemplateRequestInner (System.Collections.Generic.IList&lt;string&gt; resources = null, string options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; resources, string options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resources As IList(Of String) = null, Optional options As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner (resources, options)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="options" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resources"><span data-ttu-id="2a536-103">Die Ressourcen-Ids.</span><span class="sxs-lookup"><span data-stu-id="2a536-103">The ids of the resources.</span></span> <span data-ttu-id="2a536-104">Derzeit ist die einzige unterstützte Zeichenfolge "\*" (alle Ressourcen).</span><span class="sxs-lookup"><span data-stu-id="2a536-104">The only supported string currently is '\*' (all resources).</span></span> <span data-ttu-id="2a536-105">Exportieren von bestimmten Ressourcen unterstützt zukünftige api-Updates.</span><span class="sxs-lookup"><span data-stu-id="2a536-105">Future api updates will support exporting specific resources.</span></span></param>
        <param name="options"><span data-ttu-id="2a536-106">Der Export Vorlagenoptionen auswählen.</span><span class="sxs-lookup"><span data-stu-id="2a536-106">The export template options.</span></span> <span data-ttu-id="2a536-107">Unterstützte Werte sind "IncludeParameterDefaultValue", "IncludeComments" oder "IncludeParameterDefaultValue, IncludeComments</span><span class="sxs-lookup"><span data-stu-id="2a536-107">Supported values include 'IncludeParameterDefaultValue', 'IncludeComments' or 'IncludeParameterDefaultValue, IncludeComments</span></span></param>
        <summary>
            <span data-ttu-id="2a536-108">Initialisiert eine neue Instanz der ExportTemplateRequestInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2a536-108">Initializes a new instance of the ExportTemplateRequestInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Options">
      <MemberSignature Language="C#" Value="public string Options { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Options" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner.Options" />
      <MemberSignature Language="VB.NET" Value="Public Property Options As String" />
      <MemberSignature Language="F#" Value="member this.Options : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner.Options" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="options")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a536-109">Ruft ab oder legt den Export Vorlagenoptionen auswählen.</span><span class="sxs-lookup"><span data-stu-id="2a536-109">Gets or sets the export template options.</span></span> <span data-ttu-id="2a536-110">Unterstützte Werte sind "IncludeParameterDefaultValue", "IncludeComments" oder "IncludeParameterDefaultValue, IncludeComments</span><span class="sxs-lookup"><span data-stu-id="2a536-110">Supported values include 'IncludeParameterDefaultValue', 'IncludeComments' or 'IncludeParameterDefaultValue, IncludeComments</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a536-111">Ruft ab oder legt die Ressourcen-Ids.</span><span class="sxs-lookup"><span data-stu-id="2a536-111">Gets or sets the ids of the resources.</span></span> <span data-ttu-id="2a536-112">Derzeit ist die einzige unterstützte Zeichenfolge "\*" (alle Ressourcen).</span><span class="sxs-lookup"><span data-stu-id="2a536-112">The only supported string currently is '\*' (all resources).</span></span> <span data-ttu-id="2a536-113">Exportieren von bestimmten Ressourcen unterstützt zukünftige api-Updates.</span><span class="sxs-lookup"><span data-stu-id="2a536-113">Future api updates will support exporting specific resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>