<Type Name="NetworkRuleSet" FullName="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet">
  <TypeSignature Language="C#" Value="public class NetworkRuleSet" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkRuleSet extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkRuleSet" />
  <TypeSignature Language="F#" Value="type NetworkRuleSet = class" />
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
            <span data-ttu-id="98c89-101">Netzwerk-Regelsatz</span><span class="sxs-lookup"><span data-stu-id="98c89-101">Network rule set</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkRuleSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="98c89-102">Initialisiert eine neue Instanz der NetworkRuleSet-Klasse.</span><span class="sxs-lookup"><span data-stu-id="98c89-102">Initializes a new instance of the NetworkRuleSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkRuleSet (Microsoft.Azure.Management.Storage.Models.DefaultAction defaultAction, string bypass = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; virtualNetworkRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; ipRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Storage.Models.DefaultAction defaultAction, string bypass, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; virtualNetworkRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.IPRule&gt; ipRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.#ctor(Microsoft.Azure.Management.Storage.Models.DefaultAction,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.IPRule})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.DefaultAction * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; -&gt; Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" Usage="new Microsoft.Azure.Management.Storage.Models.NetworkRuleSet (defaultAction, bypass, virtualNetworkRules, ipRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="defaultAction" Type="Microsoft.Azure.Management.Storage.Models.DefaultAction" />
        <Parameter Name="bypass" Type="System.String" />
        <Parameter Name="virtualNetworkRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt;" />
        <Parameter Name="ipRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt;" />
      </Parameters>
      <Docs>
        <param name="defaultAction"><span data-ttu-id="98c89-103">Gibt an, die die Standardaktion des zulassen oder verweigern, wenn keine anderen Regeln übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="98c89-103">Specifies the default action of allow or deny when no other rules match.</span></span> <span data-ttu-id="98c89-104">Folgende Werte sind möglich: "Zulassen", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="98c89-104">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="bypass"><span data-ttu-id="98c89-105">Gibt an, ob Datenverkehr für die Protokollierung/Metrics/AzureServices umgangen wird.</span><span class="sxs-lookup"><span data-stu-id="98c89-105">Specifies whether traffic is bypassed for Logging/Metrics/AzureServices.</span></span> <span data-ttu-id="98c89-106">Mögliche Werte sind eine beliebige Kombination von Protokollierung | Metriken | AzureServices (z. B. "Protokollierung, Metriken") oder None keines dieser Traffics umgehen.</span><span class="sxs-lookup"><span data-stu-id="98c89-106">Possible values are any combination of Logging|Metrics|AzureServices (For example, "Logging, Metrics"), or None to bypass none of those traffics.</span></span> <span data-ttu-id="98c89-107">Folgende Werte sind möglich: "None", "Protokollierung", "Metrik", "AzureServices"</span><span class="sxs-lookup"><span data-stu-id="98c89-107">Possible values include: 'None', 'Logging', 'Metrics', 'AzureServices'</span></span></param>
        <param name="virtualNetworkRules"><span data-ttu-id="98c89-108">Legt die Regeln des virtuellen Netzwerks</span><span class="sxs-lookup"><span data-stu-id="98c89-108">Sets the virtual network rules</span></span></param>
        <param name="ipRules"><span data-ttu-id="98c89-109">Legt die IP-ACL-Regeln</span><span class="sxs-lookup"><span data-stu-id="98c89-109">Sets the IP ACL rules</span></span></param>
        <summary>
            <span data-ttu-id="98c89-110">Initialisiert eine neue Instanz der NetworkRuleSet-Klasse.</span><span class="sxs-lookup"><span data-stu-id="98c89-110">Initializes a new instance of the NetworkRuleSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Bypass">
      <MemberSignature Language="C#" Value="public string Bypass { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Bypass" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.Bypass" />
      <MemberSignature Language="VB.NET" Value="Public Property Bypass As String" />
      <MemberSignature Language="F#" Value="member this.Bypass : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.Bypass" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bypass")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98c89-111">Gibt an, ob es sich bei Datenverkehr für die Protokollierung/Metrics/AzureServices umgangen wird, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="98c89-111">Gets or sets specifies whether traffic is bypassed for Logging/Metrics/AzureServices.</span></span> <span data-ttu-id="98c89-112">Mögliche Werte sind eine beliebige Kombination von Protokollierung | Metriken | AzureServices (z. B. "Protokollierung, Metriken") oder None keines dieser Traffics umgehen.</span><span class="sxs-lookup"><span data-stu-id="98c89-112">Possible values are any combination of Logging|Metrics|AzureServices (For example, "Logging, Metrics"), or None to bypass none of those traffics.</span></span> <span data-ttu-id="98c89-113">Folgende Werte sind möglich: "None", "Protokollierung", "Metrik", "AzureServices"</span><span class="sxs-lookup"><span data-stu-id="98c89-113">Possible values include: 'None', 'Logging', 'Metrics', 'AzureServices'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.DefaultAction DefaultAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.DefaultAction DefaultAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.DefaultAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultAction As DefaultAction" />
      <MemberSignature Language="F#" Value="member this.DefaultAction : Microsoft.Azure.Management.Storage.Models.DefaultAction with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.DefaultAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.DefaultAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98c89-114">Ruft ab oder legt sie fest, gibt die Standardaktion des zulassen oder verweigern, wenn keine anderen Regeln übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="98c89-114">Gets or sets specifies the default action of allow or deny when no other rules match.</span></span> <span data-ttu-id="98c89-115">Folgende Werte sind möglich: "Zulassen", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="98c89-115">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; IpRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.IPRule&gt; IpRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.IpRules" />
      <MemberSignature Language="VB.NET" Value="Public Property IpRules As IList(Of IPRule)" />
      <MemberSignature Language="F#" Value="member this.IpRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.IpRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98c89-116">Ruft ab oder legt sie fest, legt die IP-ACL Regeln fest</span><span class="sxs-lookup"><span data-stu-id="98c89-116">Gets or sets sets the IP ACL rules</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkRuleSet.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="98c89-117">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="98c89-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="98c89-118">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="98c89-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; VirtualNetworkRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; VirtualNetworkRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.VirtualNetworkRules" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkRules As IList(Of VirtualNetworkRule)" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.VirtualNetworkRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualNetworkRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98c89-119">Ruft ab oder legt ihn fest, legt der virtuellen Netzwerkregeln</span><span class="sxs-lookup"><span data-stu-id="98c89-119">Gets or sets sets the virtual network rules</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>