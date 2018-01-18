<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="87c79-101">Eine Netzwerksicherheits-Gruppenregel an einen Endpunkt eingehenden anwenden.</span><span class="sxs-lookup"><span data-stu-id="87c79-101">A network security group rule to apply to an inbound endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87c79-102">Initialisiert eine neue Instanz der NetworkSecurityGroupRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87c79-102">Initializes a new instance of the NetworkSecurityGroupRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule : int * Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="87c79-103">Die Priorität für diese Regel.</span><span class="sxs-lookup"><span data-stu-id="87c79-103">The priority for this rule.</span></span></param>
        <param name="access"><span data-ttu-id="87c79-104">Die Aktion, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="87c79-104">The action that should be taken for a specified IP address, subnet range or tag.</span></span></param>
        <param name="sourceAddressPrefix"><span data-ttu-id="87c79-105">Der Quell-Adressenpräfix oder Tag, das für die Regel abgeglichen.</span><span class="sxs-lookup"><span data-stu-id="87c79-105">The source address prefix or tag to match for the rule.</span></span></param>
        <summary>
            <span data-ttu-id="87c79-106">Initialisiert eine neue Instanz der NetworkSecurityGroupRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87c79-106">Initializes a new instance of the NetworkSecurityGroupRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87c79-107">Ruft ab oder legt fest, die Aktion, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="87c79-107">Gets or sets the action that should be taken for a specified IP address, subnet range or tag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="87c79-108">Folgende Werte sind möglich: "zulassen", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="87c79-108">Possible values include: 'allow', 'deny'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87c79-109">Ruft ab oder legt die Priorität für diese Regel fest.</span><span class="sxs-lookup"><span data-stu-id="87c79-109">Gets or sets the priority for this rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="87c79-110">Prioritäten in einem Pool müssen eindeutig sein und werden in der Reihenfolge ihrer Priorität ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="87c79-110">Priorities within a pool must be unique and are evaluated in order of priority.</span></span> <span data-ttu-id="87c79-111">Je niedriger die Nummer ist, desto höher ist die Priorität.</span><span class="sxs-lookup"><span data-stu-id="87c79-111">The lower the number the higher the priority.</span></span> <span data-ttu-id="87c79-112">Beispielsweise können Regeln mit den Ordnungszahlen von 150, 250 und 350 angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="87c79-112">For example, rules could be specified with order numbers of 150, 250, and 350.</span></span> <span data-ttu-id="87c79-113">Die Regel mit der fortlaufenden Nummer der 150 Vorrang vor der Regel mit einer Bestellung von 250.</span><span class="sxs-lookup"><span data-stu-id="87c79-113">The rule with the order number of 150 takes precedence over the rule that has an order of 250.</span></span> <span data-ttu-id="87c79-114">Zulässige Prioritäten sind 150-3500 an.</span><span class="sxs-lookup"><span data-stu-id="87c79-114">Allowed priorities are 150 to 3500.</span></span> <span data-ttu-id="87c79-115">Wenn alle reservierten oder doppelte Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="87c79-115">If any reserved or duplicate values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87c79-116">Ruft ab oder legt das Adresspräfix der Quelle oder Tag, das für die Regel abgeglichen.</span><span class="sxs-lookup"><span data-stu-id="87c79-116">Gets or sets the source address prefix or tag to match for the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="87c79-117">Gültige Werte sind eine einzelne IP-Adresse (d. h. 10.10.10.10), die IP-Subnetz (d. h. 192.168.1.0/24), die Standard-Tag oder \* (für alle Adressen).</span><span class="sxs-lookup"><span data-stu-id="87c79-117">Valid values are a single IP address (i.e. 10.10.10.10), IP subnet (i.e. 192.168.1.0/24), default tag, or \* (for all addresses).</span></span>  <span data-ttu-id="87c79-118">Wenn ein anderer werden die Werte bereitgestellt, die Anforderung mit HTTP-Statuscode 400 ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="87c79-118">If any other values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSecurityGroupRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87c79-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="87c79-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="87c79-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="87c79-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>