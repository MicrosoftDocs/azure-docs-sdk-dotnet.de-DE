<Type Name="AliasType" FullName="Microsoft.Azure.Management.ResourceManager.Models.AliasType">
  <TypeSignature Language="C#" Value="public class AliasType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AliasType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.AliasType" />
  <TypeSignature Language="VB.NET" Value="Public Class AliasType" />
  <TypeSignature Language="F#" Value="type AliasType = class" />
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
            <span data-ttu-id="9adab-101">Der Aliastyp.</span><span class="sxs-lookup"><span data-stu-id="9adab-101">The alias type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AliasType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.AliasType.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9adab-102">Initialisiert eine neue Instanz der AliasType-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9adab-102">Initializes a new instance of the AliasType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AliasType (string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt; paths = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt; paths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.AliasType.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.AliasPathType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional paths As IList(Of AliasPathType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.AliasType : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.AliasType" Usage="new Microsoft.Azure.Management.ResourceManager.Models.AliasType (name, paths)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="paths" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9adab-103">Der Aliasname.</span><span class="sxs-lookup"><span data-stu-id="9adab-103">The alias name.</span></span></param>
        <param name="paths"><span data-ttu-id="9adab-104">Die Pfade für einen Alias.</span><span class="sxs-lookup"><span data-stu-id="9adab-104">The paths for an alias.</span></span></param>
        <summary>
            <span data-ttu-id="9adab-105">Initialisiert eine neue Instanz der AliasType-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9adab-105">Initializes a new instance of the AliasType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.AliasType.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.AliasType.Name" />
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
            <span data-ttu-id="9adab-106">Ruft ab oder legt den Aliasnamen fest.</span><span class="sxs-lookup"><span data-stu-id="9adab-106">Gets or sets the alias name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Paths">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt; Paths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt; Paths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.AliasType.Paths" />
      <MemberSignature Language="VB.NET" Value="Public Property Paths As IList(Of AliasPathType)" />
      <MemberSignature Language="F#" Value="member this.Paths : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.AliasType.Paths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="paths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.AliasPathType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9adab-107">Ruft ab oder legt die Pfade für einen Alias.</span><span class="sxs-lookup"><span data-stu-id="9adab-107">Gets or sets the paths for an alias.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>