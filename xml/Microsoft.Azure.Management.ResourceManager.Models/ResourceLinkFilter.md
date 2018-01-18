<Type Name="ResourceLinkFilter" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter">
  <TypeSignature Language="C#" Value="public class ResourceLinkFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceLinkFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceLinkFilter" />
  <TypeSignature Language="F#" Value="type ResourceLinkFilter = class" />
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
            <span data-ttu-id="6d56d-101">Filter für Ressource verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="6d56d-101">Resource link filter.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLinkFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d56d-102">Initialisiert eine neue Instanz der ResourceLinkFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d56d-102">Initializes a new instance of the ResourceLinkFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLinkFilter (string targetId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter : string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter targetId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetId"><span data-ttu-id="6d56d-103">Die ID der Zielressource.</span><span class="sxs-lookup"><span data-stu-id="6d56d-103">The ID of the target resource.</span></span></param>
        <summary>
            <span data-ttu-id="6d56d-104">Initialisiert eine neue Instanz der ResourceLinkFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d56d-104">Initializes a new instance of the ResourceLinkFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetId">
      <MemberSignature Language="C#" Value="public string TargetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter.TargetId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetId As String" />
      <MemberSignature Language="F#" Value="member this.TargetId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter.TargetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d56d-105">Ruft ab oder legt die ID der Zielressource fest.</span><span class="sxs-lookup"><span data-stu-id="6d56d-105">Gets or sets the ID of the target resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceLinkFilter.Validate " />
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
            <span data-ttu-id="6d56d-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6d56d-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6d56d-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6d56d-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>