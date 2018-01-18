<Type Name="ResourceGroupExportResult" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult">
  <TypeSignature Language="C#" Value="public class ResourceGroupExportResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceGroupExportResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceGroupExportResult" />
  <TypeSignature Language="F#" Value="type ResourceGroupExportResult = class" />
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
            <span data-ttu-id="2ec7f-101">Ressource Gruppe exportieren Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-101">Resource group export result.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroupExportResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ec7f-102">Initialisiert eine neue Instanz der ResourceGroupExportResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-102">Initializes a new instance of the ResourceGroupExportResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroupExportResult (object template = null, Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object template, class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult.#ctor(System.Object,Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional template As Object = null, Optional error As ResourceManagementErrorWithDetails = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult : obj * Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult (template, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="template" Type="System.Object" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails" />
      </Parameters>
      <Docs>
        <param name="template"><span data-ttu-id="2ec7f-103">Der Inhalt der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-103">The template content.</span></span></param>
        <param name="error"><span data-ttu-id="2ec7f-104">Der Fehler.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-104">The error.</span></span></param>
        <summary>
            <span data-ttu-id="2ec7f-105">Initialisiert eine neue Instanz der ResourceGroupExportResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-105">Initializes a new instance of the ResourceGroupExportResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ResourceManagementErrorWithDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ec7f-106">Ruft ab oder legt den Fehler.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-106">Gets or sets the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public object Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As Object" />
      <MemberSignature Language="F#" Value="member this.Template : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult.Template" />
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
            <span data-ttu-id="2ec7f-107">Ruft ab oder legt den Vorlageninhalt.</span><span class="sxs-lookup"><span data-stu-id="2ec7f-107">Gets or sets the template content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>