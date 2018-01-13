<Type Name="ServerFirewallRuleInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner">
  <TypeSignature Language="C#" Value="public class ServerFirewallRuleInner : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerFirewallRuleInner extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerFirewallRuleInner&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type ServerFirewallRuleInner = class&#xA;    inherit SqlSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3d6aa-101">Stellt eine Firewallregel für Azure SQL-Server dar.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-101">Represents an Azure SQL server firewall rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerFirewallRuleInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3d6aa-102">Initialisiert eine neue Instanz der ServerFirewallRuleInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-102">Initializes a new instance of the ServerFirewallRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerFirewallRuleInner (string name = null, string id = null, string kind = null, string location = null, string startIpAddress = null, string endIpAddress = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string kind, string location, string startIpAddress, string endIpAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional kind As String = null, Optional location As String = null, Optional startIpAddress As String = null, Optional endIpAddress As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner (name, id, kind, location, startIpAddress, endIpAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3d6aa-103">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="3d6aa-103">Resource name</span></span></param>
        <param name="id"><span data-ttu-id="3d6aa-104">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-104">The resource ID.</span></span></param>
        <param name="kind"><span data-ttu-id="3d6aa-105">Der Typ des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-105">Kind of server that contains this firewall rule.</span></span></param>
        <param name="location"><span data-ttu-id="3d6aa-106">Der Speicherort des Servers, der diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-106">Location of the server that contains this firewall rule.</span></span></param>
        <param name="startIpAddress"><span data-ttu-id="3d6aa-107">Die Start-IP-Adresse der Firewallregel für Azure SQL-Server.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-107">The start IP address of the Azure SQL server firewall rule.</span></span> <span data-ttu-id="3d6aa-108">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-108">Must be IPv4 format.</span></span></param>
        <param name="endIpAddress"><span data-ttu-id="3d6aa-109">Die End-IP-Adresse der Firewallregel für Azure SQL-Server.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-109">The end IP address of the Azure SQL server firewall rule.</span></span> <span data-ttu-id="3d6aa-110">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-110">Must be IPv4 format.</span></span></param>
        <summary>
            <span data-ttu-id="3d6aa-111">Initialisiert eine neue Instanz der ServerFirewallRuleInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-111">Initializes a new instance of the ServerFirewallRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3d6aa-112">Ermittelt oder definiert die End-IP-Adresse des Azure SQL Server-Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-112">Gets or sets the end IP address of the Azure SQL server firewall rule.</span></span> <span data-ttu-id="3d6aa-113">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-113">Must be IPv4 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3d6aa-114">Ruft den Typ des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-114">Gets kind of server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3d6aa-115">Ruft die Adresse des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-115">Gets location of the server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3d6aa-116">Ruft ab oder legt die erste IP-Adresse des Azure SQL-Servers Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-116">Gets or sets the start IP address of the Azure SQL server firewall rule.</span></span> <span data-ttu-id="3d6aa-117">Muss im IPv4-Format vorliegen.</span><span class="sxs-lookup"><span data-stu-id="3d6aa-117">Must be IPv4 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>