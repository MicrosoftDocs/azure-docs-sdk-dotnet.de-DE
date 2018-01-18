<Type Name="GenericResourceInner" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner">
  <TypeSignature Language="C#" Value="public class GenericResourceInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GenericResourceInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class GenericResourceInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type GenericResourceInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a9c5c-101">Informationen zur Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-101">Resource information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GenericResourceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-102">Initialisiert eine neue Instanz der GenericResourceInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-102">Initializes a new instance of the GenericResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GenericResourceInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan plan = null, object properties = null, string kind = null, string managedBy = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku sku = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity identity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan plan, object properties, string kind, string managedBy, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku sku, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan,System.Object,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku,Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan * obj * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku * Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner (location, id, name, type, tags, plan, properties, kind, managedBy, sku, identity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan" />
        <Parameter Name="properties" Type="System.Object" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="managedBy" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="plan"><span data-ttu-id="a9c5c-103">Der Plan der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-103">The plan of the resource.</span></span></param>
        <param name="properties"><span data-ttu-id="a9c5c-104">Die Ressourceneigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-104">The resource properties.</span></span></param>
        <param name="kind"><span data-ttu-id="a9c5c-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-105">The kind of the resource.</span></span></param>
        <param name="managedBy"><span data-ttu-id="a9c5c-106">Die ID der Ressource, die diese Ressource verwaltet.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-106">Id of the resource that manages this resource.</span></span></param>
        <param name="sku"><span data-ttu-id="a9c5c-107">Die Sku der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-107">The sku of the resource.</span></span></param>
        <param name="identity"><span data-ttu-id="a9c5c-108">Die Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-108">The identity of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="a9c5c-109">Initialisiert eine neue Instanz der GenericResourceInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-109">Initializes a new instance of the GenericResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-110">Ruft ab oder legt die Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-110">Gets or sets the identity of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-111">Ruft ab oder legt die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-111">Gets or sets the kind of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedBy">
      <MemberSignature Language="C#" Value="public string ManagedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.ManagedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedBy As String" />
      <MemberSignature Language="F#" Value="member this.ManagedBy : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.ManagedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-112">Ruft ab oder legt die Id der Ressource, die diese Ressource verwaltet.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-112">Gets or sets id of the resource that manages this resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-113">Ruft ab oder legt den Plan der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-113">Gets or sets the plan of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-114">Ruft ab oder legt die Ressourceneigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-114">Gets or sets the resource properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9c5c-115">Ruft ab oder legt die Sku der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a9c5c-115">Gets or sets the sku of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>