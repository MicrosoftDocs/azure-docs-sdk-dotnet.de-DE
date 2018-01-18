<Type Name="SubscriptionDefinition" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition">
  <TypeSignature Language="C#" Value="public class SubscriptionDefinition : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionDefinition extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionDefinition&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinition = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="87ede-101">Die Abonnementdefinition verwendet, um das Abonnement zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="87ede-101">The subscription definition used to create the subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87ede-102">Initialisiert eine neue Instanz der SubscriptionDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87ede-102">Initializes a new instance of the SubscriptionDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinition (string id = null, string name = null, string type = null, string subscriptionId = null, string subscriptionDisplayName = null, string offerType = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string subscriptionId, string subscriptionDisplayName, string offerType, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional subscriptionId As String = null, Optional subscriptionDisplayName As String = null, Optional offerType As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition (id, name, type, subscriptionId, subscriptionDisplayName, offerType, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="subscriptionDisplayName" Type="System.String" />
        <Parameter Name="offerType" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="87ede-103">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="87ede-103">The resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="87ede-104">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="87ede-104">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="87ede-105">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="87ede-105">The type of the resource.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="87ede-106">Die ID des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87ede-106">The ID of the subscription.</span></span></param>
        <param name="subscriptionDisplayName"><span data-ttu-id="87ede-107">Der Anzeigename des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87ede-107">The display name of the subscription.</span></span></param>
        <param name="offerType"><span data-ttu-id="87ede-108">Der Angebotstyp des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87ede-108">The offer type of the subscription.</span></span> <span data-ttu-id="87ede-109">MS-AZR - 0017 P (EnterpriseAgreement) und MS-AZR - 0148 P (EnterpriseAgreement DevTest) ist, kann z. B. verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="87ede-109">For example, MS-AZR-0017P (EnterpriseAgreement) and MS-AZR-0148P (EnterpriseAgreement devTest) are available.</span></span></param>
        <param name="etag"><span data-ttu-id="87ede-110">Das Etag der Abonnementdefinition.</span><span class="sxs-lookup"><span data-stu-id="87ede-110">The etag the subscription definition.</span></span></param>
        <summary>
            <span data-ttu-id="87ede-111">Initialisiert eine neue Instanz der SubscriptionDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87ede-111">Initializes a new instance of the SubscriptionDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ede-112">Ruft ab oder legt das Etag die Abonnementdefinition fest.</span><span class="sxs-lookup"><span data-stu-id="87ede-112">Gets or sets the etag the subscription definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="87ede-113">Ruft die ID der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="87ede-113">Gets the resource ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Name" />
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
            <span data-ttu-id="87ede-114">Ruft den Namen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="87ede-114">Gets the name of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OfferType">
      <MemberSignature Language="C#" Value="public string OfferType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OfferType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.OfferType" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferType As String" />
      <MemberSignature Language="F#" Value="member this.OfferType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.OfferType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.offerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ede-115">Ruft ab oder legt der Angebotstyp des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87ede-115">Gets or sets the offer type of the subscription.</span></span> <span data-ttu-id="87ede-116">MS-AZR - 0017 P (EnterpriseAgreement) und MS-AZR - 0148 P (EnterpriseAgreement DevTest) ist, kann z. B. verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="87ede-116">For example, MS-AZR-0017P (EnterpriseAgreement) and MS-AZR-0148P (EnterpriseAgreement devTest) are available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionDisplayName">
      <MemberSignature Language="C#" Value="public string SubscriptionDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.SubscriptionDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionDisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.SubscriptionDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ede-117">Ruft ab oder legt den Anzeigenamen des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87ede-117">Gets or sets the display name of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ede-118">Ruft die ID des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="87ede-118">Gets the ID of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ede-119">Ruft den Typ der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="87ede-119">Gets the type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>