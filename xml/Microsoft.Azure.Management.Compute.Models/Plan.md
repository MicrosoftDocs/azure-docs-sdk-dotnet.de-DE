<Type Name="Plan" FullName="Microsoft.Azure.Management.Compute.Models.Plan">
  <TypeSignature Language="C#" Value="public class Plan" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Plan extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Plan" />
  <TypeSignature Language="VB.NET" Value="Public Class Plan" />
  <TypeSignature Language="F#" Value="type Plan = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="223ba-101">Gibt Informationen zu den Marketplace-Image zum Erstellen des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="223ba-101">Specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="223ba-102">Dieses Element wird nur für Marketplace-Images verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="223ba-102">This element is only used for marketplace images.</span></span>
            <span data-ttu-id="223ba-103">Bevor Sie einem Marketplace-Image aus einer API verwenden können, müssen Sie das Bild zur programmgesteuerten Verwendung aktivieren.</span><span class="sxs-lookup"><span data-stu-id="223ba-103">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="223ba-104">Suchen Sie im Azure-Portal Marketplace-Image, das Sie verwenden möchten und klicken Sie dann auf **bereitzustellende programmgesteuert, erste Schritte -&gt;**.</span><span class="sxs-lookup"><span data-stu-id="223ba-104">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&gt;**.</span></span> <span data-ttu-id="223ba-105">Geben Sie alle erforderlichen Informationen ein, und klicken Sie dann auf **speichern**.</span><span class="sxs-lookup"><span data-stu-id="223ba-105">Enter any required information and then click **Save**.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Plan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Plan.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="223ba-106">Initialisiert eine neue Instanz der Plan-Klasse.</span><span class="sxs-lookup"><span data-stu-id="223ba-106">Initializes a new instance of the Plan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Plan (string name = null, string publisher = null, string product = null, string promotionCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string publisher, string product, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Plan.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional publisher As String = null, Optional product As String = null, Optional promotionCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Plan : string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Plan" Usage="new Microsoft.Azure.Management.Compute.Models.Plan (name, publisher, product, promotionCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="223ba-107">Die Plan-ID</span><span class="sxs-lookup"><span data-stu-id="223ba-107">The plan ID.</span></span></param>
        <param name="publisher"><span data-ttu-id="223ba-108">Die Herausgeber-ID.</span><span class="sxs-lookup"><span data-stu-id="223ba-108">The publisher ID.</span></span></param>
        <param name="product"><span data-ttu-id="223ba-109">Gibt das Produkt des Images aus dem Marketplace an.</span><span class="sxs-lookup"><span data-stu-id="223ba-109">Specifies the product of the image from the marketplace.</span></span> <span data-ttu-id="223ba-110">Dies ist der gleiche Wert wie Angebot unter dem ImageReference-Element.</span><span class="sxs-lookup"><span data-stu-id="223ba-110">This is the same value as Offer under the imageReference element.</span></span></param>
        <param name="promotionCode"><span data-ttu-id="223ba-111">Der Promotionscode.</span><span class="sxs-lookup"><span data-stu-id="223ba-111">The promotion code.</span></span></param>
        <summary>
            <span data-ttu-id="223ba-112">Initialisiert eine neue Instanz der Plan-Klasse.</span><span class="sxs-lookup"><span data-stu-id="223ba-112">Initializes a new instance of the Plan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="223ba-113">Ruft ab oder legt die Plan-ID</span><span class="sxs-lookup"><span data-stu-id="223ba-113">Gets or sets the plan ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Product" />
      <MemberSignature Language="VB.NET" Value="Public Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Product" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="product")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="223ba-114">Ruft ab oder legt gibt das Produkt des Images aus dem Marketplace an.</span><span class="sxs-lookup"><span data-stu-id="223ba-114">Gets or sets specifies the product of the image from the marketplace.</span></span> <span data-ttu-id="223ba-115">Dies ist der gleiche Wert wie Angebot unter dem ImageReference-Element.</span><span class="sxs-lookup"><span data-stu-id="223ba-115">This is the same value as Offer under the imageReference element.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PromotionCode">
      <MemberSignature Language="C#" Value="public string PromotionCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PromotionCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.PromotionCode" />
      <MemberSignature Language="VB.NET" Value="Public Property PromotionCode As String" />
      <MemberSignature Language="F#" Value="member this.PromotionCode : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.PromotionCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="promotionCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="223ba-116">Ruft ab oder legt den Promotioncode.</span><span class="sxs-lookup"><span data-stu-id="223ba-116">Gets or sets the promotion code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="223ba-117">Ruft ab oder legt die Herausgeber-ID.</span><span class="sxs-lookup"><span data-stu-id="223ba-117">Gets or sets the publisher ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>