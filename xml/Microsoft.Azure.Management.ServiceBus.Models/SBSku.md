<Type Name="SBSku" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBSku">
  <TypeSignature Language="C#" Value="public class SBSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBSku" />
  <TypeSignature Language="VB.NET" Value="Public Class SBSku" />
  <TypeSignature Language="F#" Value="type SBSku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24e08-101">SKU des Namespaces.</span><span class="sxs-lookup"><span data-stu-id="24e08-101">SKU of the namespace.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBSku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24e08-102">Initialisiert eine neue Instanz der SBSku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="24e08-102">Initializes a new instance of the SBSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBSku (Microsoft.Azure.Management.ServiceBus.Models.SkuName name, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt; tier = null, Nullable&lt;int&gt; capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.ServiceBus.Models.SkuName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt; tier, valuetype System.Nullable`1&lt;int32&gt; capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBSku.#ctor(Microsoft.Azure.Management.ServiceBus.Models.SkuName,System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.SkuTier},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName, Optional tier As Nullable(Of SkuTier) = null, Optional capacity As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBSku : Microsoft.Azure.Management.ServiceBus.Models.SkuName * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBSku" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBSku (name, tier, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.ServiceBus.Models.SkuName" />
        <Parameter Name="tier" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt;" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="24e08-103">Der Name dieser SKU.</span><span class="sxs-lookup"><span data-stu-id="24e08-103">Name of this SKU.</span></span> <span data-ttu-id="24e08-104">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="24e08-104">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="tier"><span data-ttu-id="24e08-105">Die abrechnungsebene dieser bestimmten SKU.</span><span class="sxs-lookup"><span data-stu-id="24e08-105">The billing tier of this particular SKU.</span></span>
            <span data-ttu-id="24e08-106">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="24e08-106">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="capacity"><span data-ttu-id="24e08-107">Die angegebene messaging Einheiten für die Ebene.</span><span class="sxs-lookup"><span data-stu-id="24e08-107">The specified messaging units for the tier.</span></span>
            <span data-ttu-id="24e08-108">Kapazität für Premium-Dienstebene sind 1,2 und 4.</span><span class="sxs-lookup"><span data-stu-id="24e08-108">For Premium tier, capacity are 1,2 and 4.</span></span></param>
        <summary>
            <span data-ttu-id="24e08-109">Initialisiert eine neue Instanz der SBSku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="24e08-109">Initializes a new instance of the SBSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24e08-110">Ruft ab oder legt die angegebenen messaging Einheiten für die Ebene.</span><span class="sxs-lookup"><span data-stu-id="24e08-110">Gets or sets the specified messaging units for the tier.</span></span> <span data-ttu-id="24e08-111">Kapazität für Premium-Dienstebene sind 1,2 und 4.</span><span class="sxs-lookup"><span data-stu-id="24e08-111">For Premium tier, capacity are 1,2 and 4.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ServiceBus.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.ServiceBus.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24e08-112">Ruft ab oder legt den Namen dieser SKU fest.</span><span class="sxs-lookup"><span data-stu-id="24e08-112">Gets or sets name of this SKU.</span></span> <span data-ttu-id="24e08-113">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="24e08-113">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt; Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt; Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As Nullable(Of SkuTier)" />
      <MemberSignature Language="F#" Value="member this.Tier : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.SkuTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24e08-114">Ruft ab oder legt die abrechnungsebene dieser bestimmten SKU.</span><span class="sxs-lookup"><span data-stu-id="24e08-114">Gets or sets the billing tier of this particular SKU.</span></span> <span data-ttu-id="24e08-115">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="24e08-115">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBSku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sBSku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24e08-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="24e08-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="24e08-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="24e08-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>