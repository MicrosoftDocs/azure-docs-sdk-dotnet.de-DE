<Type Name="HostNameSslState" FullName="Microsoft.Azure.Management.WebSites.Models.HostNameSslState">
  <TypeSignature Language="C#" Value="public class HostNameSslState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostNameSslState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HostNameSslState" />
  <TypeSignature Language="VB.NET" Value="Public Class HostNameSslState" />
  <TypeSignature Language="F#" Value="type HostNameSslState = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="400d1-101">SSL aktivierten Hostnamen.</span><span class="sxs-lookup"><span data-stu-id="400d1-101">SSL-enabled hostname.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameSslState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="400d1-102">Initialisiert eine neue Instanz der HostNameSslState-Klasse.</span><span class="sxs-lookup"><span data-stu-id="400d1-102">Initializes a new instance of the HostNameSslState class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameSslState (string name = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; sslState = null, string virtualIP = null, string thumbprint = null, Nullable&lt;bool&gt; toUpdate = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostType&gt; hostType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SslState&gt; sslState, string virtualIP, string thumbprint, valuetype System.Nullable`1&lt;bool&gt; toUpdate, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostType&gt; hostType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.SslState},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.WebSites.Models.HostType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional sslState As Nullable(Of SslState) = null, Optional virtualIP As String = null, Optional thumbprint As String = null, Optional toUpdate As Nullable(Of Boolean) = null, Optional hostType As Nullable(Of HostType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HostNameSslState : string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostType&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.HostNameSslState" Usage="new Microsoft.Azure.Management.WebSites.Models.HostNameSslState (name, sslState, virtualIP, thumbprint, toUpdate, hostType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sslState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt;" />
        <Parameter Name="virtualIP" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="toUpdate" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="400d1-103">Hostname.</span><span class="sxs-lookup"><span data-stu-id="400d1-103">Hostname.</span></span></param>
        <param name="sslState"><span data-ttu-id="400d1-104">SSL-Typ.</span><span class="sxs-lookup"><span data-stu-id="400d1-104">SSL type.</span></span> <span data-ttu-id="400d1-105">Folgende Werte sind möglich: "Deaktiviert", "SniEnabled", "IpBasedEnabled"</span><span class="sxs-lookup"><span data-stu-id="400d1-105">Possible values include: 'Disabled', 'SniEnabled', 'IpBasedEnabled'</span></span></param>
        <param name="virtualIP"><span data-ttu-id="400d1-106">Virtuelle IP-Adresse, den Hostnamen zugewiesen, wenn die IP-basiertes SSL aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="400d1-106">Virtual IP address assigned to the hostname if IP based SSL is enabled.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="400d1-107">Fingerabdruck des SSL-Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="400d1-107">SSL certificate thumbprint.</span></span></param>
        <param name="toUpdate"><span data-ttu-id="400d1-108">Legen Sie auf &lt;Code&gt;"true"&lt;/code&gt; vorhandenen Hostnamen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="400d1-108">Set to &lt;code&gt;true&lt;/code&gt; to update existing hostname.</span></span></param>
        <param name="hostType"><span data-ttu-id="400d1-109">Gibt an, ob der Hostname ein Standard oder Repository-Hostname ist.</span><span class="sxs-lookup"><span data-stu-id="400d1-109">Indicates whether the hostname is a standard or repository hostname.</span></span> <span data-ttu-id="400d1-110">Folgende Werte sind möglich: 'Standard', 'Repository'</span><span class="sxs-lookup"><span data-stu-id="400d1-110">Possible values include: 'Standard', 'Repository'</span></span></param>
        <summary>
            <span data-ttu-id="400d1-111">Initialisiert eine neue Instanz der HostNameSslState-Klasse.</span><span class="sxs-lookup"><span data-stu-id="400d1-111">Initializes a new instance of the HostNameSslState class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostType&gt; HostType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostType&gt; HostType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.HostType" />
      <MemberSignature Language="VB.NET" Value="Public Property HostType As Nullable(Of HostType)" />
      <MemberSignature Language="F#" Value="member this.HostType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameSslState.HostType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="400d1-112">Gibt an, ob der Hostname ist ein Standard oder Repository-Hostname, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="400d1-112">Gets or sets indicates whether the hostname is a standard or repository hostname.</span></span> <span data-ttu-id="400d1-113">Folgende Werte sind möglich: 'Standard', 'Repository'</span><span class="sxs-lookup"><span data-stu-id="400d1-113">Possible values include: 'Standard', 'Repository'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameSslState.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="400d1-114">Ruft ab, oder legt ihn fest Hostname.</span><span class="sxs-lookup"><span data-stu-id="400d1-114">Gets or sets hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; SslState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SslState&gt; SslState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.SslState" />
      <MemberSignature Language="VB.NET" Value="Public Property SslState As Nullable(Of SslState)" />
      <MemberSignature Language="F#" Value="member this.SslState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameSslState.SslState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sslState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="400d1-115">Ruft ab oder legt ihn fest SSL.</span><span class="sxs-lookup"><span data-stu-id="400d1-115">Gets or sets SSL type.</span></span> <span data-ttu-id="400d1-116">Folgende Werte sind möglich: "Deaktiviert", "SniEnabled", "IpBasedEnabled"</span><span class="sxs-lookup"><span data-stu-id="400d1-116">Possible values include: 'Disabled', 'SniEnabled', 'IpBasedEnabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameSslState.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="400d1-117">Abrufen oder Festlegen der Fingerabdruck des SSL-Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="400d1-117">Gets or sets SSL certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToUpdate">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ToUpdate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ToUpdate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.ToUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Property ToUpdate As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ToUpdate : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameSslState.ToUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="toUpdate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="400d1-118">Ruft ab oder legt diese fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; vorhandenen Hostnamen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="400d1-118">Gets or sets set to &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to update existing hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualIP">
      <MemberSignature Language="C#" Value="public string VirtualIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameSslState.VirtualIP" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualIP As String" />
      <MemberSignature Language="F#" Value="member this.VirtualIP : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameSslState.VirtualIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="400d1-119">Ruft ab oder legt ihn fest, die virtuelle IP-Adresse, den Hostnamen zugewiesen, wenn die IP-basiertes SSL aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="400d1-119">Gets or sets virtual IP address assigned to the hostname if IP based SSL is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>