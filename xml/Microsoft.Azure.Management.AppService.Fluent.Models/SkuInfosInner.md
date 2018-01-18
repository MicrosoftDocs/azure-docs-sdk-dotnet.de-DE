<Type Name="SkuInfosInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner">
  <TypeSignature Language="C#" Value="public class SkuInfosInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SkuInfosInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SkuInfosInner" />
  <TypeSignature Language="F#" Value="type SkuInfosInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ad95a-101">Die Auflistung der SKU-Informationen.</span><span class="sxs-lookup"><span data-stu-id="ad95a-101">Collection of SKU information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuInfosInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ad95a-102">Initialisiert eine neue Instanz der SkuInfosInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ad95a-102">Initializes a new instance of the SkuInfosInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuInfosInner (string resourceType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt; skus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt; skus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional skus As IList(Of GlobalCsmSkuDescription) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner (resourceType, skus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="skus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="ad95a-103">Der Ressourcentyp, die dieser SKU gilt.</span><span class="sxs-lookup"><span data-stu-id="ad95a-103">Resource type that this SKU applies to.</span></span></param>
        <param name="skus"><span data-ttu-id="ad95a-104">Liste von SKUs, die das Abonnement verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="ad95a-104">List of SKUs the subscription is able to use.</span></span></param>
        <summary>
            <span data-ttu-id="ad95a-105">Initialisiert eine neue Instanz der SkuInfosInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ad95a-105">Initializes a new instance of the SkuInfosInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad95a-106">Ruft ab, oder legt ihn fest Ressourcentyp, der dieser SKU gilt.</span><span class="sxs-lookup"><span data-stu-id="ad95a-106">Gets or sets resource type that this SKU applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt; Skus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt; Skus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner.Skus" />
      <MemberSignature Language="VB.NET" Value="Public Property Skus As IList(Of GlobalCsmSkuDescription)" />
      <MemberSignature Language="F#" Value="member this.Skus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfosInner.Skus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.GlobalCsmSkuDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad95a-107">Ruft ab, oder legt ihn fest Liste von SKUs des Abonnements verwenden kann.</span><span class="sxs-lookup"><span data-stu-id="ad95a-107">Gets or sets list of SKUs the subscription is able to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>