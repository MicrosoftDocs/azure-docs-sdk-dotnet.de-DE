<Type Name="FirewallRule" FullName="Microsoft.Azure.Management.Sql.Models.FirewallRule">
  <TypeSignature Language="C#" Value="public class FirewallRule : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FirewallRule extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Class FirewallRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type FirewallRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fc281-101">Stellt eine Server-Firewall-Regel dar.</span><span class="sxs-lookup"><span data-stu-id="fc281-101">Represents a server firewall rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FirewallRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fc281-102">Initialisiert eine neue Instanz der FirewallRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fc281-102">Initializes a new instance of the FirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule (string startIpAddress, string endIpAddress, string id = null, string name = null, string type = null, string kind = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIpAddress, string endIpAddress, string id, string name, string type, string kind, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FirewallRule.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startIpAddress As String, endIpAddress As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FirewallRule : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FirewallRule" Usage="new Microsoft.Azure.Management.Sql.Models.FirewallRule (startIpAddress, endIpAddress, id, name, type, kind, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIpAddress"><span data-ttu-id="fc281-103">Die erste IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fc281-103">The start IP address of the firewall rule.</span></span> <span data-ttu-id="fc281-104">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="fc281-104">Must be IPv4 format.</span></span> <span data-ttu-id="fc281-105">Verwenden der Wert "0.0.0.0" alle Azure-internen IP-Adressen darstellen.</span><span class="sxs-lookup"><span data-stu-id="fc281-105">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span></param>
        <param name="endIpAddress"><span data-ttu-id="fc281-106">Die letzte IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fc281-106">The end IP address of the firewall rule.</span></span>
            <span data-ttu-id="fc281-107">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="fc281-107">Must be IPv4 format.</span></span> <span data-ttu-id="fc281-108">Muss größer als oder gleich beim Start sein.</span><span class="sxs-lookup"><span data-stu-id="fc281-108">Must be greater than or equal to startIpAddress.</span></span> <span data-ttu-id="fc281-109">Verwenden der Wert "0.0.0.0" alle Azure-internen IP-Adressen darstellen.</span><span class="sxs-lookup"><span data-stu-id="fc281-109">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span></param>
        <param name="id"><span data-ttu-id="fc281-110">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="fc281-110">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="fc281-111">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="fc281-111">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="fc281-112">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="fc281-112">Resource type.</span></span></param>
        <param name="kind"><span data-ttu-id="fc281-113">Der Typ des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="fc281-113">Kind of server that contains this firewall rule.</span></span></param>
        <param name="location"><span data-ttu-id="fc281-114">Der Speicherort des Servers, der diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="fc281-114">Location of the server that contains this firewall rule.</span></span></param>
        <summary>
            <span data-ttu-id="fc281-115">Initialisiert eine neue Instanz der FirewallRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fc281-115">Initializes a new instance of the FirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="fc281-116">Ruft ab oder legt die IP-Endadresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fc281-116">Gets or sets the end IP address of the firewall rule.</span></span> <span data-ttu-id="fc281-117">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="fc281-117">Must be IPv4 format.</span></span> <span data-ttu-id="fc281-118">Muss größer als oder gleich beim Start sein.</span><span class="sxs-lookup"><span data-stu-id="fc281-118">Must be greater than or equal to startIpAddress.</span></span> <span data-ttu-id="fc281-119">Verwenden der Wert "0.0.0.0" alle Azure-internen IP-Adressen darstellen.</span><span class="sxs-lookup"><span data-stu-id="fc281-119">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="fc281-120">Ruft den Typ des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="fc281-120">Gets kind of server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc281-121">Ruft die Adresse des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="fc281-121">Gets location of the server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="fc281-122">Ruft ab oder legt die erste IP-Adresse der Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="fc281-122">Gets or sets the start IP address of the firewall rule.</span></span> <span data-ttu-id="fc281-123">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="fc281-123">Must be IPv4 format.</span></span> <span data-ttu-id="fc281-124">Verwenden der Wert "0.0.0.0" alle Azure-internen IP-Adressen darstellen.</span><span class="sxs-lookup"><span data-stu-id="fc281-124">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FirewallRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="firewallRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fc281-125">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="fc281-125">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fc281-126">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="fc281-126">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>