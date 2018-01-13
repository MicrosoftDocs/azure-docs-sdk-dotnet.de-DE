<Type Name="ResourcesMoveInfoInner" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner">
  <TypeSignature Language="C#" Value="public class ResourcesMoveInfoInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourcesMoveInfoInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourcesMoveInfoInner" />
  <TypeSignature Language="F#" Value="type ResourcesMoveInfoInner = class" />
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
            <span data-ttu-id="5fa95-101">Parameter der Ressourcen verschieben.</span><span class="sxs-lookup"><span data-stu-id="5fa95-101">Parameters of move resources.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourcesMoveInfoInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5fa95-102">Initialisiert eine neue Instanz der ResourcesMoveInfoInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fa95-102">Initializes a new instance of the ResourcesMoveInfoInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourcesMoveInfoInner (System.Collections.Generic.IList&lt;string&gt; resources = null, string targetResourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; resources, string targetResourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resources As IList(Of String) = null, Optional targetResourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner (resources, targetResourceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="targetResourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resources"><span data-ttu-id="5fa95-103">Die Ressourcen-Ids.</span><span class="sxs-lookup"><span data-stu-id="5fa95-103">The ids of the resources.</span></span></param>
        <param name="targetResourceGroup"><span data-ttu-id="5fa95-104">Die Zielressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5fa95-104">The target resource group.</span></span></param>
        <summary>
            <span data-ttu-id="5fa95-105">Initialisiert eine neue Instanz der ResourcesMoveInfoInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fa95-105">Initializes a new instance of the ResourcesMoveInfoInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner.Resources" />
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
            <span data-ttu-id="5fa95-106">Ruft ab oder legt die Ressourcen-Ids.</span><span class="sxs-lookup"><span data-stu-id="5fa95-106">Gets or sets the ids of the resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceGroup">
      <MemberSignature Language="C#" Value="public string TargetResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner.TargetResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourcesMoveInfoInner.TargetResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fa95-107">Ruft ab oder legt die Zielressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5fa95-107">Gets or sets the target resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>