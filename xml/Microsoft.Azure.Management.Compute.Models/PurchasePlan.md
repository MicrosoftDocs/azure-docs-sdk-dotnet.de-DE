<Type Name="PurchasePlan" FullName="Microsoft.Azure.Management.Compute.Models.PurchasePlan">
  <TypeSignature Language="C#" Value="public class PurchasePlan" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PurchasePlan extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.PurchasePlan" />
  <TypeSignature Language="VB.NET" Value="Public Class PurchasePlan" />
  <TypeSignature Language="F#" Value="type PurchasePlan = class" />
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
            <span data-ttu-id="c4558-101">Zum Einrichten von Purchase-Rahmen 3rd Party Artefakten über MarketPlace verwendet.</span><span class="sxs-lookup"><span data-stu-id="c4558-101">Used for establishing the purchase context of any 3rd Party artifact through MarketPlace.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PurchasePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.PurchasePlan.#ctor" />
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
            <span data-ttu-id="c4558-102">Initialisiert eine neue Instanz der PurchasePlan-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c4558-102">Initializes a new instance of the PurchasePlan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PurchasePlan (string publisher, string name, string product);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string publisher, string name, string product) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.PurchasePlan.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (publisher As String, name As String, product As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.PurchasePlan : string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.PurchasePlan" Usage="new Microsoft.Azure.Management.Compute.Models.PurchasePlan (publisher, name, product)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher"><span data-ttu-id="c4558-103">Die Herausgeber-ID.</span><span class="sxs-lookup"><span data-stu-id="c4558-103">The publisher ID.</span></span></param>
        <param name="name"><span data-ttu-id="c4558-104">Die Plan-ID</span><span class="sxs-lookup"><span data-stu-id="c4558-104">The plan ID.</span></span></param>
        <param name="product"><span data-ttu-id="c4558-105">Gibt das Produkt des Images aus dem Marketplace an.</span><span class="sxs-lookup"><span data-stu-id="c4558-105">Specifies the product of the image from the marketplace.</span></span> <span data-ttu-id="c4558-106">Dies ist der gleiche Wert wie Angebot unter dem ImageReference-Element.</span><span class="sxs-lookup"><span data-stu-id="c4558-106">This is the same value as Offer under the imageReference element.</span></span></param>
        <summary>
            <span data-ttu-id="c4558-107">Initialisiert eine neue Instanz der PurchasePlan-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c4558-107">Initializes a new instance of the PurchasePlan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.PurchasePlan.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.PurchasePlan.Name" />
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
            <span data-ttu-id="c4558-108">Ruft ab oder legt die Plan-ID</span><span class="sxs-lookup"><span data-stu-id="c4558-108">Gets or sets the plan ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.PurchasePlan.Product" />
      <MemberSignature Language="VB.NET" Value="Public Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.PurchasePlan.Product" />
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
            <span data-ttu-id="c4558-109">Ruft ab oder legt gibt das Produkt des Images aus dem Marketplace an.</span><span class="sxs-lookup"><span data-stu-id="c4558-109">Gets or sets specifies the product of the image from the marketplace.</span></span> <span data-ttu-id="c4558-110">Dies ist der gleiche Wert wie Angebot unter dem ImageReference-Element.</span><span class="sxs-lookup"><span data-stu-id="c4558-110">This is the same value as Offer under the imageReference element.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.PurchasePlan.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.PurchasePlan.Publisher" />
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
            <span data-ttu-id="c4558-111">Ruft ab oder legt die Herausgeber-ID.</span><span class="sxs-lookup"><span data-stu-id="c4558-111">Gets or sets the publisher ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.PurchasePlan.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="purchasePlan.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4558-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c4558-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c4558-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c4558-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>