<Type Name="IpsecPolicy" FullName="Microsoft.Azure.Management.Network.Models.IpsecPolicy">
  <TypeSignature Language="C#" Value="public class IpsecPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IpsecPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.IpsecPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class IpsecPolicy" />
  <TypeSignature Language="F#" Value="type IpsecPolicy = class" />
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
            <span data-ttu-id="5d4d0-101">Eine IPSec-Richtlinienkonfiguration für ein virtuelles Netzwerk-Gateway-Verbindung</span><span class="sxs-lookup"><span data-stu-id="5d4d0-101">An IPSec Policy configuration for a virtual network gateway connection</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpsecPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IpsecPolicy.#ctor" />
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
            <span data-ttu-id="5d4d0-102">Initialisiert eine neue Instanz der Klasse IpsecPolicy an.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-102">Initializes a new instance of the IpsecPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpsecPolicy (int saLifeTimeSeconds, int saDataSizeKilobytes, string ipsecEncryption, string ipsecIntegrity, string ikeEncryption, string ikeIntegrity, string dhGroup, string pfsGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 saLifeTimeSeconds, int32 saDataSizeKilobytes, string ipsecEncryption, string ipsecIntegrity, string ikeEncryption, string ikeIntegrity, string dhGroup, string pfsGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IpsecPolicy.#ctor(System.Int32,System.Int32,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (saLifeTimeSeconds As Integer, saDataSizeKilobytes As Integer, ipsecEncryption As String, ipsecIntegrity As String, ikeEncryption As String, ikeIntegrity As String, dhGroup As String, pfsGroup As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.IpsecPolicy : int * int * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.IpsecPolicy" Usage="new Microsoft.Azure.Management.Network.Models.IpsecPolicy (saLifeTimeSeconds, saDataSizeKilobytes, ipsecEncryption, ipsecIntegrity, ikeEncryption, ikeIntegrity, dhGroup, pfsGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="saLifeTimeSeconds" Type="System.Int32" />
        <Parameter Name="saDataSizeKilobytes" Type="System.Int32" />
        <Parameter Name="ipsecEncryption" Type="System.String" />
        <Parameter Name="ipsecIntegrity" Type="System.String" />
        <Parameter Name="ikeEncryption" Type="System.String" />
        <Parameter Name="ikeIntegrity" Type="System.String" />
        <Parameter Name="dhGroup" Type="System.String" />
        <Parameter Name="pfsGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="saLifeTimeSeconds"><span data-ttu-id="5d4d0-103">Die IPSec-Sicherheitszuordnungsangebote (so genannte Schnellmodus oder Phase 2 SA) Lebensdauer in Sekunden für einen Standort-zu-Standort-VPN-Tunnel.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-103">The IPSec Security Association (also called Quick Mode or Phase 2 SA) lifetime in seconds for a site to site VPN tunnel.</span></span></param>
        <param name="saDataSizeKilobytes"><span data-ttu-id="5d4d0-104">Die IPSec-Sicherheitszuordnungsangebote (auch als Quick-Modus oder Phase 2 SA) Nutzlastgröße in KB für einen Standort-zu-Standort-VPN-Tunnel.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-104">The IPSec Security Association (also called Quick Mode or Phase 2 SA) payload size in KB for a site to site VPN tunnel.</span></span></param>
        <param name="ipsecEncryption"><span data-ttu-id="5d4d0-105">Der IPSec-Verschlüsselungsalgorithmus (IKE Phase 1).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-105">The IPSec encryption algorithm (IKE phase 1).</span></span> <span data-ttu-id="5d4d0-106">Folgende Werte sind möglich: 'None', 'DES' "DES3" aes128 "und" "AES192" "AES256" "GCMAES128" "GCMAES192", "GCMAES256"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-106">Possible values include: 'None', 'DES', 'DES3', 'AES128', 'AES192', 'AES256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span></param>
        <param name="ipsecIntegrity"><span data-ttu-id="5d4d0-107">Der IPSec-Integrität-Algorithmus (IKE Phase 1).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-107">The IPSec integrity algorithm (IKE phase 1).</span></span> <span data-ttu-id="5d4d0-108">Folgende Werte sind möglich: "MD5", "SHA1", "SHA256", "GCMAES128", "GCMAES192", "GCMAES256"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-108">Possible values include: 'MD5', 'SHA1', 'SHA256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span></param>
        <param name="ikeEncryption"><span data-ttu-id="5d4d0-109">Der IKE-Verschlüsselungsalgorithmus (IKE Phase 2).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-109">The IKE encryption algorithm (IKE phase 2).</span></span> <span data-ttu-id="5d4d0-110">Folgende Werte sind möglich: "DES", "DES3", "AES128", "AES192", "AES256"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-110">Possible values include: 'DES', 'DES3', 'AES128', 'AES192', 'AES256'</span></span></param>
        <param name="ikeIntegrity"><span data-ttu-id="5d4d0-111">Der IKE-Integrität-Algorithmus (IKE Phase 2).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-111">The IKE integrity algorithm (IKE phase 2).</span></span> <span data-ttu-id="5d4d0-112">Folgende Werte sind möglich: "MD5", "SHA1", "SHA256", "SHA384"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-112">Possible values include: 'MD5', 'SHA1', 'SHA256', 'SHA384'</span></span></param>
        <param name="dhGroup"><span data-ttu-id="5d4d0-113">Die DH-Gruppen für das anfängliche SA IKE Phase 1 verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-113">The DH Groups used in IKE Phase 1 for initial SA.</span></span> <span data-ttu-id="5d4d0-114">Folgende Werte sind möglich: 'None', 'DHGroup1', "DHGroup2", "DHGroup14", "DHGroup2048", "ECP256", "ECP384", "DHGroup24"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-114">Possible values include: 'None', 'DHGroup1', 'DHGroup2', 'DHGroup14', 'DHGroup2048', 'ECP256', 'ECP384', 'DHGroup24'</span></span></param>
        <param name="pfsGroup"><span data-ttu-id="5d4d0-115">Die DH-Gruppen, die für das neue untergeordnete SA in IKE Phase 2 verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-115">The DH Groups used in IKE Phase 2 for new child SA.</span></span> <span data-ttu-id="5d4d0-116">Folgende Werte sind möglich: 'None', 'PFS1', 'PFS2', "PFS2048", "ECP256", "ECP384", "PFS24"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-116">Possible values include: 'None', 'PFS1', 'PFS2', 'PFS2048', 'ECP256', 'ECP384', 'PFS24'</span></span></param>
        <summary>
            <span data-ttu-id="5d4d0-117">Initialisiert eine neue Instanz der Klasse IpsecPolicy an.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-117">Initializes a new instance of the IpsecPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DhGroup">
      <MemberSignature Language="C#" Value="public string DhGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DhGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.DhGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property DhGroup As String" />
      <MemberSignature Language="F#" Value="member this.DhGroup : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.DhGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dhGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-118">Ermittelt oder definiert die DH-Gruppen, die für das anfängliche SA IKE Phase 1 verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-118">Gets or sets the DH Groups used in IKE Phase 1 for initial SA.</span></span>
            <span data-ttu-id="5d4d0-119">Folgende Werte sind möglich: 'None', 'DHGroup1', "DHGroup2", "DHGroup14", "DHGroup2048", "ECP256", "ECP384", "DHGroup24"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-119">Possible values include: 'None', 'DHGroup1', 'DHGroup2', 'DHGroup14', 'DHGroup2048', 'ECP256', 'ECP384', 'DHGroup24'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IkeEncryption">
      <MemberSignature Language="C#" Value="public string IkeEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IkeEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property IkeEncryption As String" />
      <MemberSignature Language="F#" Value="member this.IkeEncryption : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ikeEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-120">Ruft ab oder legt den IKE-Verschlüsselungsalgorithmus (IKE Phase 2).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-120">Gets or sets the IKE encryption algorithm (IKE phase 2).</span></span> <span data-ttu-id="5d4d0-121">Folgende Werte sind möglich: "DES", "DES3", "AES128", "AES192", "AES256"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-121">Possible values include: 'DES', 'DES3', 'AES128', 'AES192', 'AES256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IkeIntegrity">
      <MemberSignature Language="C#" Value="public string IkeIntegrity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IkeIntegrity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeIntegrity" />
      <MemberSignature Language="VB.NET" Value="Public Property IkeIntegrity As String" />
      <MemberSignature Language="F#" Value="member this.IkeIntegrity : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeIntegrity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ikeIntegrity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-122">Ermittelt oder definiert IKE-Integrität-Algorithmus (IKE Phase 2).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-122">Gets or sets the IKE integrity algorithm (IKE phase 2).</span></span> <span data-ttu-id="5d4d0-123">Folgende Werte sind möglich: "MD5", "SHA1", "SHA256", "SHA384"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-123">Possible values include: 'MD5', 'SHA1', 'SHA256', 'SHA384'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsecEncryption">
      <MemberSignature Language="C#" Value="public string IpsecEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpsecEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsecEncryption As String" />
      <MemberSignature Language="F#" Value="member this.IpsecEncryption : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipsecEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-124">Ruft ab oder legt den Verschlüsselungsalgorithmus IPSec (IKE Phase 1).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-124">Gets or sets the IPSec encryption algorithm (IKE phase 1).</span></span> <span data-ttu-id="5d4d0-125">Folgende Werte sind möglich: 'None', 'DES' "DES3" aes128 "und" "AES192" "AES256" "GCMAES128" "GCMAES192", "GCMAES256"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-125">Possible values include: 'None', 'DES', 'DES3', 'AES128', 'AES192', 'AES256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsecIntegrity">
      <MemberSignature Language="C#" Value="public string IpsecIntegrity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpsecIntegrity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecIntegrity" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsecIntegrity As String" />
      <MemberSignature Language="F#" Value="member this.IpsecIntegrity : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecIntegrity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipsecIntegrity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-126">Ruft ab oder legt den Hashalgorithmus für IPSec-Integrität (IKE Phase 1).</span><span class="sxs-lookup"><span data-stu-id="5d4d0-126">Gets or sets the IPSec integrity algorithm (IKE phase 1).</span></span> <span data-ttu-id="5d4d0-127">Folgende Werte sind möglich: "MD5", "SHA1", "SHA256", "GCMAES128", "GCMAES192", "GCMAES256"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-127">Possible values include: 'MD5', 'SHA1', 'SHA256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PfsGroup">
      <MemberSignature Language="C#" Value="public string PfsGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PfsGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.PfsGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property PfsGroup As String" />
      <MemberSignature Language="F#" Value="member this.PfsGroup : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.PfsGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pfsGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-128">Abrufen oder Festlegen der DH-Gruppen, die für das neue untergeordnete SA IKE Phase 2 verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-128">Gets or sets the DH Groups used in IKE Phase 2 for new child SA.</span></span>
            <span data-ttu-id="5d4d0-129">Folgende Werte sind möglich: 'None', 'PFS1', 'PFS2', "PFS2048", "ECP256", "ECP384", "PFS24"</span><span class="sxs-lookup"><span data-stu-id="5d4d0-129">Possible values include: 'None', 'PFS1', 'PFS2', 'PFS2048', 'ECP256', 'ECP384', 'PFS24'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaDataSizeKilobytes">
      <MemberSignature Language="C#" Value="public int SaDataSizeKilobytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SaDataSizeKilobytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaDataSizeKilobytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SaDataSizeKilobytes As Integer" />
      <MemberSignature Language="F#" Value="member this.SaDataSizeKilobytes : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaDataSizeKilobytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="saDataSizeKilobytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-130">Ruft ab, oder legt fest die Nutzlastgröße für IPSec-Sicherheitszuordnungsangebote (so genannte Schnellmodus oder Phase 2 SA) in KB für einen Standort-zu-Standort-VPN-Tunnel.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-130">Gets or sets the IPSec Security Association (also called Quick Mode or Phase 2 SA) payload size in KB for a site to site VPN tunnel.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaLifeTimeSeconds">
      <MemberSignature Language="C#" Value="public int SaLifeTimeSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SaLifeTimeSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaLifeTimeSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property SaLifeTimeSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.SaLifeTimeSeconds : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaLifeTimeSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="saLifeTimeSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-131">Ruft ab oder legt die IPSec-Sicherheitszuordnungsangebote (so genannte Schnellmodus oder Phase 2 SA) Lebensdauer in Sekunden für einen Standort-zu-Standort-VPN-Tunnel.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-131">Gets or sets the IPSec Security Association (also called Quick Mode or Phase 2 SA) lifetime in seconds for a site to site VPN tunnel.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IpsecPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="ipsecPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d4d0-132">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5d4d0-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4d0-133">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5d4d0-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>