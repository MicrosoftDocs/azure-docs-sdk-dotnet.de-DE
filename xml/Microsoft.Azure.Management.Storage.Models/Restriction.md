<Type Name="Restriction" FullName="Microsoft.Azure.Management.Storage.Models.Restriction">
  <TypeSignature Language="C#" Value="public class Restriction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Restriction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Restriction" />
  <TypeSignature Language="VB.NET" Value="Public Class Restriction" />
  <TypeSignature Language="F#" Value="type Restriction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="37915-101">Die Einschränkung, die aufgrund, die SKU verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="37915-101">The restriction because of which SKU cannot be used.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Restriction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Restriction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="37915-102">Initialisiert eine neue Instanz der Klasse Einschränkung an.</span><span class="sxs-lookup"><span data-stu-id="37915-102">Initializes a new instance of the Restriction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Restriction (string type = null, System.Collections.Generic.IList&lt;string&gt; values = null, string reasonCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, class System.Collections.Generic.IList`1&lt;string&gt; values, string reasonCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Restriction.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional values As IList(Of String) = null, Optional reasonCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Restriction : string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Storage.Models.Restriction" Usage="new Microsoft.Azure.Management.Storage.Models.Restriction (type, values, reasonCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="reasonCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="37915-103">Der Typ der Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="37915-103">The type of restrictions.</span></span> <span data-ttu-id="37915-104">Ab jetzt wird nur möglicher Wert für diesen Speicherort.</span><span class="sxs-lookup"><span data-stu-id="37915-104">As of now only possible value for this is location.</span></span></param>
        <param name="values"><span data-ttu-id="37915-105">Der Wert der Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="37915-105">The value of restrictions.</span></span> <span data-ttu-id="37915-106">Wenn Sie den Typ der Einschränkung auf Speicherort festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="37915-106">If the restriction type is set to location.</span></span> <span data-ttu-id="37915-107">Dies wäre Speicherorte, in denen die SKU beschränkt ist.</span><span class="sxs-lookup"><span data-stu-id="37915-107">This would be different locations where the SKU is restricted.</span></span></param>
        <param name="reasonCode"><span data-ttu-id="37915-108">Der Grund für die Einschränkung.</span><span class="sxs-lookup"><span data-stu-id="37915-108">The reason for the restriction.</span></span> <span data-ttu-id="37915-109">Ab jetzt kann dies ""quotaid "" oder "NotAvailableForSubscription" sein.</span><span class="sxs-lookup"><span data-stu-id="37915-109">As of now this can be “QuotaId” or “NotAvailableForSubscription”.</span></span> <span data-ttu-id="37915-110">Kontingent-Id wird festgelegt, wenn die SKU RequiredQuotas Parameter verfügt, wie das Abonnement nicht zu diesem Kontingent gehört.</span><span class="sxs-lookup"><span data-stu-id="37915-110">Quota Id is set when the SKU has requiredQuotas parameter as the subscription does not belong to that quota.</span></span> <span data-ttu-id="37915-111">Die "NotAvailableForSubscription" bezieht sich auf Kapazität auf Domänencontroller.</span><span class="sxs-lookup"><span data-stu-id="37915-111">The “NotAvailableForSubscription” is related to capacity at DC.</span></span> <span data-ttu-id="37915-112">Folgende Werte sind möglich: "quotaid" "", "NotAvailableForSubscription"</span><span class="sxs-lookup"><span data-stu-id="37915-112">Possible values include: 'QuotaId', 'NotAvailableForSubscription'</span></span></param>
        <summary>
            <span data-ttu-id="37915-113">Initialisiert eine neue Instanz der Klasse Einschränkung an.</span><span class="sxs-lookup"><span data-stu-id="37915-113">Initializes a new instance of the Restriction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonCode">
      <MemberSignature Language="C#" Value="public string ReasonCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReasonCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Restriction.ReasonCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReasonCode As String" />
      <MemberSignature Language="F#" Value="member this.ReasonCode : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Restriction.ReasonCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reasonCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37915-114">Ruft ab oder legt den Grund für die Einschränkung.</span><span class="sxs-lookup"><span data-stu-id="37915-114">Gets or sets the reason for the restriction.</span></span> <span data-ttu-id="37915-115">Ab jetzt kann dies ""quotaid "" oder "NotAvailableForSubscription" sein.</span><span class="sxs-lookup"><span data-stu-id="37915-115">As of now this can be “QuotaId” or “NotAvailableForSubscription”.</span></span> <span data-ttu-id="37915-116">Kontingent-Id wird festgelegt, wenn die SKU RequiredQuotas Parameter verfügt, wie das Abonnement nicht zu diesem Kontingent gehört.</span><span class="sxs-lookup"><span data-stu-id="37915-116">Quota Id is set when the SKU has requiredQuotas parameter as the subscription does not belong to that quota.</span></span> <span data-ttu-id="37915-117">Die "NotAvailableForSubscription" bezieht sich auf Kapazität auf Domänencontroller.</span><span class="sxs-lookup"><span data-stu-id="37915-117">The “NotAvailableForSubscription” is related to capacity at DC.</span></span> <span data-ttu-id="37915-118">Folgende Werte sind möglich: "quotaid" "", "NotAvailableForSubscription"</span><span class="sxs-lookup"><span data-stu-id="37915-118">Possible values include: 'QuotaId', 'NotAvailableForSubscription'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Restriction.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Storage.Models.Restriction.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="37915-119">Ruft den Typ von Einschränkungen ab.</span><span class="sxs-lookup"><span data-stu-id="37915-119">Gets the type of restrictions.</span></span> <span data-ttu-id="37915-120">Ab jetzt wird nur möglicher Wert für diesen Speicherort.</span><span class="sxs-lookup"><span data-stu-id="37915-120">As of now only possible value for this is location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Restriction.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Restriction.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37915-121">Ruft den Wert von Einschränkungen ab.</span><span class="sxs-lookup"><span data-stu-id="37915-121">Gets the value of restrictions.</span></span> <span data-ttu-id="37915-122">Wenn Sie den Typ der Einschränkung auf Speicherort festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="37915-122">If the restriction type is set to location.</span></span> <span data-ttu-id="37915-123">Dies wäre Speicherorte, in denen die SKU beschränkt ist.</span><span class="sxs-lookup"><span data-stu-id="37915-123">This would be different locations where the SKU is restricted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>