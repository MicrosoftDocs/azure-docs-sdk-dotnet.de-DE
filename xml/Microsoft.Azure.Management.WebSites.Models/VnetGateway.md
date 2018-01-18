<Type Name="VnetGateway" FullName="Microsoft.Azure.Management.WebSites.Models.VnetGateway">
  <TypeSignature Language="C#" Value="public class VnetGateway : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetGateway extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetGateway" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetGateway&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetGateway = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a478a-101">Der Vertrag für den Virtuellenetzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="a478a-101">The Virtual Network gateway contract.</span></span> <span data-ttu-id="a478a-102">Hiermit wird das Virtuellenetzwerk-Gateway-Zugriff auf die VPN-Clientpaket zu gewähren.</span><span class="sxs-lookup"><span data-stu-id="a478a-102">This is used to give the Virtual Network gateway access to the VPN package.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetGateway ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetGateway.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a478a-103">Initialisiert eine neue Instanz der VnetGateway-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a478a-103">Initializes a new instance of the VnetGateway class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetGateway (string id = null, string name = null, string kind = null, string type = null, string vnetName = null, string vpnPackageUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetName, string vpnPackageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetGateway.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetName As String = null, Optional vpnPackageUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetGateway : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetGateway" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetGateway (id, name, kind, type, vnetName, vpnPackageUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vpnPackageUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a478a-104">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="a478a-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="a478a-105">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="a478a-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="a478a-106">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a478a-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="a478a-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="a478a-107">Resource type.</span></span></param>
        <param name="vnetName"><span data-ttu-id="a478a-108">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a478a-108">The Virtual Network name.</span></span></param>
        <param name="vpnPackageUri"><span data-ttu-id="a478a-109">Der URI, in denen das VPN-Paket heruntergeladen werden kann.</span><span class="sxs-lookup"><span data-stu-id="a478a-109">The URI where the VPN package can be downloaded.</span></span></param>
        <summary>
            <span data-ttu-id="a478a-110">Initialisiert eine neue Instanz der VnetGateway-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a478a-110">Initializes a new instance of the VnetGateway class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetGateway.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetGateway.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a478a-111">Ruft ab oder legt den Namen des virtuellen Netzwerks fest.</span><span class="sxs-lookup"><span data-stu-id="a478a-111">Gets or sets the Virtual Network name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnPackageUri">
      <MemberSignature Language="C#" Value="public string VpnPackageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VpnPackageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetGateway.VpnPackageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnPackageUri As String" />
      <MemberSignature Language="F#" Value="member this.VpnPackageUri : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetGateway.VpnPackageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnPackageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a478a-112">Ruft ab oder legt den URI, in denen das VPN-Paket heruntergeladen werden kann.</span><span class="sxs-lookup"><span data-stu-id="a478a-112">Gets or sets the URI where the VPN package can be downloaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>