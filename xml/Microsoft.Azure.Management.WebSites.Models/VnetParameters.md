<Type Name="VnetParameters" FullName="Microsoft.Azure.Management.WebSites.Models.VnetParameters">
  <TypeSignature Language="C#" Value="public class VnetParameters : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetParameters extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetParameters&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetParameters = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="25b71-101">Der erforderliche Gruppe der Eingaben, um ein VNET zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="25b71-101">The required set of inputs to validate a VNET</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25b71-102">Initialisiert eine neue Instanz der VnetParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25b71-102">Initializes a new instance of the VnetParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetParameters (string id = null, string name = null, string kind = null, string type = null, string vnetResourceGroup = null, string vnetName = null, string vnetSubnetName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetResourceGroup, string vnetName, string vnetSubnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetParameters.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetResourceGroup As String = null, Optional vnetName As String = null, Optional vnetSubnetName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetParameters : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetParameters" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetParameters (id, name, kind, type, vnetResourceGroup, vnetName, vnetSubnetName)" />
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
        <Parameter Name="vnetResourceGroup" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vnetSubnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="25b71-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="25b71-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="25b71-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="25b71-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="25b71-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="25b71-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="25b71-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="25b71-106">Resource type.</span></span></param>
        <param name="vnetResourceGroup"><span data-ttu-id="25b71-107">Die Ressourcengruppe des VNETS überprüft werden</span><span class="sxs-lookup"><span data-stu-id="25b71-107">The Resource Group of the VNET to be validated</span></span></param>
        <param name="vnetName"><span data-ttu-id="25b71-108">Der Name des VNETS überprüft werden</span><span class="sxs-lookup"><span data-stu-id="25b71-108">The name of the VNET to be validated</span></span></param>
        <param name="vnetSubnetName"><span data-ttu-id="25b71-109">Der Subnetzname überprüft werden</span><span class="sxs-lookup"><span data-stu-id="25b71-109">The subnet name to be validated</span></span></param>
        <summary>
            <span data-ttu-id="25b71-110">Initialisiert eine neue Instanz der VnetParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25b71-110">Initializes a new instance of the VnetParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetParameters.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetParameters.VnetName" />
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
            <span data-ttu-id="25b71-111">Ruft ab oder legt den Namen des VNETS überprüft werden</span><span class="sxs-lookup"><span data-stu-id="25b71-111">Gets or sets the name of the VNET to be validated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceGroup">
      <MemberSignature Language="C#" Value="public string VnetResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetParameters.VnetResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetParameters.VnetResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetResourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25b71-112">Ruft ab oder legt die Ressourcengruppe des VNETS überprüft werden</span><span class="sxs-lookup"><span data-stu-id="25b71-112">Gets or sets the Resource Group of the VNET to be validated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetSubnetName">
      <MemberSignature Language="C#" Value="public string VnetSubnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetSubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetParameters.VnetSubnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetSubnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetSubnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetParameters.VnetSubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetSubnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25b71-113">Ruft ab oder legt den Subnetznamen an, die überprüft werden</span><span class="sxs-lookup"><span data-stu-id="25b71-113">Gets or sets the subnet name to be validated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>