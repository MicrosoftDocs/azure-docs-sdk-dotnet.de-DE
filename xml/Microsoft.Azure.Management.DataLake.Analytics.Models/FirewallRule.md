<Type Name="FirewallRule" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule">
  <TypeSignature Language="C#" Value="public class FirewallRule : Microsoft.Azure.Management.DataLake.Analytics.Models.OptionalSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FirewallRule extends Microsoft.Azure.Management.DataLake.Analytics.Models.OptionalSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Class FirewallRule&#xA;Inherits OptionalSubResource" />
  <TypeSignature Language="F#" Value="type FirewallRule = class&#xA;    inherit OptionalSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.OptionalSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="465eb-101">Data Lake Analytics Regel Firewallinformationen</span><span class="sxs-lookup"><span data-stu-id="465eb-101">Data Lake Analytics firewall rule information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="465eb-102">Initialisiert eine neue Instanz der FirewallRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="465eb-102">Initializes a new instance of the FirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule (string startIpAddress, string endIpAddress, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIpAddress, string endIpAddress, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startIpAddress As String, endIpAddress As String, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule : string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule (startIpAddress, endIpAddress, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIpAddress"><span data-ttu-id="465eb-103">die erste IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="465eb-103">the start IP address for the firewall rule.</span></span> <span data-ttu-id="465eb-104">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="465eb-104">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="465eb-105">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="465eb-105">Start and End should be in the same protocol.</span></span></param>
        <param name="endIpAddress"><span data-ttu-id="465eb-106">die letzte IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="465eb-106">the end IP address for the firewall rule.</span></span> <span data-ttu-id="465eb-107">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="465eb-107">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="465eb-108">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="465eb-108">Start and End should be in the same protocol.</span></span></param>
        <param name="id"><span data-ttu-id="465eb-109">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="465eb-109">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="465eb-110">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="465eb-110">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="465eb-111">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="465eb-111">Resource type</span></span></param>
        <summary>
            <span data-ttu-id="465eb-112">Initialisiert eine neue Instanz der FirewallRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="465eb-112">Initializes a new instance of the FirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="465eb-113">Ruft ab oder legt die IP-Endadresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="465eb-113">Gets or sets the end IP address for the firewall rule.</span></span> <span data-ttu-id="465eb-114">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="465eb-114">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="465eb-115">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="465eb-115">Start and End should be in the same protocol.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="465eb-116">Ruft ab oder legt die erste IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="465eb-116">Gets or sets the start IP address for the firewall rule.</span></span> <span data-ttu-id="465eb-117">Dies kann entweder ipv4 oder ipv6 sein.</span><span class="sxs-lookup"><span data-stu-id="465eb-117">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="465eb-118">Anfangs- und Enddatum sollte in das gleiche Protokoll.</span><span class="sxs-lookup"><span data-stu-id="465eb-118">Start and End should be in the same protocol.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="firewallRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="465eb-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="465eb-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="465eb-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="465eb-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>