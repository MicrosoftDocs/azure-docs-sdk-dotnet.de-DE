<Type Name="UpdateFirewallRuleParameters" FullName="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters">
  <TypeSignature Language="C#" Value="public class UpdateFirewallRuleParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateFirewallRuleParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateFirewallRuleParameters" />
  <TypeSignature Language="F#" Value="type UpdateFirewallRuleParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6c15a-101">Update-Parameter der Data Lake Analytics-Firewall-Regel</span><span class="sxs-lookup"><span data-stu-id="6c15a-101">Data Lake Analytics firewall rule update parameters</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateFirewallRuleParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c15a-102">Initialisiert eine neue Instanz der UpdateFirewallRuleParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6c15a-102">Initializes a new instance of the UpdateFirewallRuleParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateFirewallRuleParameters (string startIpAddress = null, string endIpAddress = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIpAddress, string endIpAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startIpAddress As String = null, Optional endIpAddress As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters (startIpAddress, endIpAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIpAddress"><span data-ttu-id="6c15a-103">die erste IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="6c15a-103">the start IP address for the firewall rule.</span></span> <span data-ttu-id="6c15a-104">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="6c15a-104">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="6c15a-105">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="6c15a-105">Start and End should be in the same protocol.</span></span></param>
        <param name="endIpAddress"><span data-ttu-id="6c15a-106">die letzte IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="6c15a-106">the end IP address for the firewall rule.</span></span> <span data-ttu-id="6c15a-107">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="6c15a-107">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="6c15a-108">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="6c15a-108">Start and End should be in the same protocol.</span></span></param>
        <summary>
            <span data-ttu-id="6c15a-109">Initialisiert eine neue Instanz der UpdateFirewallRuleParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6c15a-109">Initializes a new instance of the UpdateFirewallRuleParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c15a-110">Ruft ab oder legt die IP-Endadresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="6c15a-110">Gets or sets the end IP address for the firewall rule.</span></span> <span data-ttu-id="6c15a-111">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="6c15a-111">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="6c15a-112">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="6c15a-112">Start and End should be in the same protocol.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c15a-113">Ruft ab oder legt die erste IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="6c15a-113">Gets or sets the start IP address for the firewall rule.</span></span> <span data-ttu-id="6c15a-114">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="6c15a-114">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="6c15a-115">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="6c15a-115">Start and End should be in the same protocol.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>