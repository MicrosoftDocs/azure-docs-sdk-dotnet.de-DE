<Type Name="TagValueInner" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner">
  <TypeSignature Language="C#" Value="public class TagValueInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TagValueInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TagValueInner" />
  <TypeSignature Language="F#" Value="type TagValueInner = class" />
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
            <span data-ttu-id="4a423-101">Informationen zu kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="4a423-101">Tag information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagValueInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4a423-102">Initialisiert eine neue Instanz der TagValueInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4a423-102">Initializes a new instance of the TagValueInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagValueInner (string id = null, string tagValueProperty = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tagValueProperty, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.#ctor(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional tagValueProperty As String = null, Optional count As TagCount = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner : string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner (id, tagValueProperty, count)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tagValueProperty" Type="System.String" />
        <Parameter Name="count" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="4a423-103">Die Transponder-ID.</span><span class="sxs-lookup"><span data-stu-id="4a423-103">The tag ID.</span></span></param>
        <param name="tagValueProperty"><span data-ttu-id="4a423-104">Der Tagwert.</span><span class="sxs-lookup"><span data-stu-id="4a423-104">The tag value.</span></span></param>
        <param name="count"><span data-ttu-id="4a423-105">Die Anzahl der Tagwerte.</span><span class="sxs-lookup"><span data-stu-id="4a423-105">The tag value count.</span></span></param>
        <summary>
            <span data-ttu-id="4a423-106">Initialisiert eine neue Instanz der TagValueInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4a423-106">Initializes a new instance of the TagValueInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As TagCount" />
      <MemberSignature Language="F#" Value="member this.Count : Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagCount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4a423-107">Ruft ab oder legt die Anzahl der Tagwerte.</span><span class="sxs-lookup"><span data-stu-id="4a423-107">Gets or sets the tag value count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="4a423-108">Ruft ab oder legt die Transponder-ID.</span><span class="sxs-lookup"><span data-stu-id="4a423-108">Gets or sets the tag ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagValueProperty">
      <MemberSignature Language="C#" Value="public string TagValueProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagValueProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.TagValueProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property TagValueProperty As String" />
      <MemberSignature Language="F#" Value="member this.TagValueProperty : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TagValueInner.TagValueProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tagValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4a423-109">Ruft ab oder legt den Tagwert fest.</span><span class="sxs-lookup"><span data-stu-id="4a423-109">Gets or sets the tag value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>