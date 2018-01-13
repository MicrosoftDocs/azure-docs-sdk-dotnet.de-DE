<Type Name="ConnectivityIssue" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityIssue">
  <TypeSignature Language="C#" Value="public class ConnectivityIssue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityIssue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityIssue" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityIssue" />
  <TypeSignature Language="F#" Value="type ConnectivityIssue = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83507-101">Informationen zu einem Problem gerade Konnektivität wird überprüft.</span><span class="sxs-lookup"><span data-stu-id="83507-101">Information about an issue encountered in the process of checking for connectivity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityIssue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83507-102">Initialisiert eine neue Instanz der ConnectivityIssue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="83507-102">Initializes a new instance of the ConnectivityIssue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityIssue (string origin = null, string severity = null, string type = null, System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; context = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string origin, string severity, string type, class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.Collections.Generic.IDictionary{System.String,System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional origin As String = null, Optional severity As String = null, Optional type As String = null, Optional context As IList(Of IDictionary(Of String, String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityIssue : string * string * string * System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string, string&gt;&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityIssue" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityIssue (origin, severity, type, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="severity" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="context" Type="System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="origin"><span data-ttu-id="83507-103">Der Ursprung des Problems.</span><span class="sxs-lookup"><span data-stu-id="83507-103">The origin of the issue.</span></span> <span data-ttu-id="83507-104">Folgende Werte sind möglich: 'Local', 'Eingehend', 'Ausgehend'</span><span class="sxs-lookup"><span data-stu-id="83507-104">Possible values include: 'Local', 'Inbound', 'Outbound'</span></span></param>
        <param name="severity"><span data-ttu-id="83507-105">Der Schweregrad des Problems.</span><span class="sxs-lookup"><span data-stu-id="83507-105">The severity of the issue.</span></span> <span data-ttu-id="83507-106">Folgende Werte sind möglich: "Fehler", "Warnung"</span><span class="sxs-lookup"><span data-stu-id="83507-106">Possible values include: 'Error', 'Warning'</span></span></param>
        <param name="type"><span data-ttu-id="83507-107">Der Typ des Problems.</span><span class="sxs-lookup"><span data-stu-id="83507-107">The type of issue.</span></span> <span data-ttu-id="83507-108">Folgende Werte sind möglich: "Unknown", "AgentStopped" "GuestFirewall" "DnsResolution" "SocketBind" "NetworkSecurityRule" 'UserDefinedRoute' 'PortThrottled', 'Plattform'</span><span class="sxs-lookup"><span data-stu-id="83507-108">Possible values include: 'Unknown', 'AgentStopped', 'GuestFirewall', 'DnsResolution', 'SocketBind', 'NetworkSecurityRule', 'UserDefinedRoute', 'PortThrottled', 'Platform'</span></span></param>
        <param name="context"><span data-ttu-id="83507-109">Stellt zusätzlichen Kontext bereit, auf das Problem.</span><span class="sxs-lookup"><span data-stu-id="83507-109">Provides additional context on the issue.</span></span></param>
        <summary>
            <span data-ttu-id="83507-110">Initialisiert eine neue Instanz der ConnectivityIssue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="83507-110">Initializes a new instance of the ConnectivityIssue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As IList(Of IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.Context : System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string, string&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="context")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83507-111">Ruft stellt zusätzlichen Kontext bereit, auf das Problem.</span><span class="sxs-lookup"><span data-stu-id="83507-111">Gets provides additional context on the issue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Origin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83507-112">Ruft den Ursprung des Problems ab.</span><span class="sxs-lookup"><span data-stu-id="83507-112">Gets the origin of the issue.</span></span> <span data-ttu-id="83507-113">Folgende Werte sind möglich: 'Local', 'Eingehend', 'Ausgehend'</span><span class="sxs-lookup"><span data-stu-id="83507-113">Possible values include: 'Local', 'Inbound', 'Outbound'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public string Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As String" />
      <MemberSignature Language="F#" Value="member this.Severity : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83507-114">Ruft den Schweregrad des Problems ab.</span><span class="sxs-lookup"><span data-stu-id="83507-114">Gets the severity of the issue.</span></span> <span data-ttu-id="83507-115">Folgende Werte sind möglich: "Fehler", "Warnung"</span><span class="sxs-lookup"><span data-stu-id="83507-115">Possible values include: 'Error', 'Warning'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="83507-116">Ruft den Typ des Problems ab.</span><span class="sxs-lookup"><span data-stu-id="83507-116">Gets the type of issue.</span></span> <span data-ttu-id="83507-117">Folgende Werte sind möglich: "Unknown", "AgentStopped" "GuestFirewall" "DnsResolution" "SocketBind" "NetworkSecurityRule" 'UserDefinedRoute' 'PortThrottled', 'Plattform'</span><span class="sxs-lookup"><span data-stu-id="83507-117">Possible values include: 'Unknown', 'AgentStopped', 'GuestFirewall', 'DnsResolution', 'SocketBind', 'NetworkSecurityRule', 'UserDefinedRoute', 'PortThrottled', 'Platform'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>