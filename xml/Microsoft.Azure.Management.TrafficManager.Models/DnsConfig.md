<Type Name="DnsConfig" FullName="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig">
  <TypeSignature Language="C#" Value="public class DnsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DnsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class DnsConfig" />
  <TypeSignature Language="F#" Value="type DnsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="39cd1-101">Die Klasse, die DNS-Einstellungen in einem Traffic Manager-Profil enthält.</span><span class="sxs-lookup"><span data-stu-id="39cd1-101">Class containing DNS settings in a Traffic Manager profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DnsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="39cd1-102">Initialisiert eine neue Instanz der Klasse DnsConfig an.</span><span class="sxs-lookup"><span data-stu-id="39cd1-102">Initializes a new instance of the DnsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DnsConfig (string relativeName = null, string fqdn = null, Nullable&lt;long&gt; ttl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relativeName, string fqdn, valuetype System.Nullable`1&lt;int64&gt; ttl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.#ctor(System.String,System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional relativeName As String = null, Optional fqdn As String = null, Optional ttl As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.DnsConfig : string * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" Usage="new Microsoft.Azure.Management.TrafficManager.Models.DnsConfig (relativeName, fqdn, ttl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relativeName" Type="System.String" />
        <Parameter Name="fqdn" Type="System.String" />
        <Parameter Name="ttl" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="relativeName"><span data-ttu-id="39cd1-103">Ruft ab oder legt den relativen DNS-Namen, die von diesem Traffic Manager-Profil bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="39cd1-103">Gets or sets the relative DNS name provided by this Traffic Manager profile.</span></span>  <span data-ttu-id="39cd1-104">Dieser Wert wird mit dem DNS-Domänennamen kombiniert, der von Azure Traffic Manager zum Erstellen des vollqualifizierten Domänennamens (FQDN) des Profils verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="39cd1-104">This value is combined with the DNS domain name used by Azure Traffic Manager to form the fully-qualified domain name (FQDN) of the profile.</span></span></param>
        <param name="fqdn"><span data-ttu-id="39cd1-105">Ruft ab oder legt den vollqualifizierten Domänennamen (FQDN) des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="39cd1-105">Gets or sets the fully-qualified domain name (FQDN) of the Traffic Manager profile.</span></span>  <span data-ttu-id="39cd1-106">Dies bildet aus der Verkettung von RelativeName mit der DNS-Domäne von Azure Traffic Manager verwendet.</span><span class="sxs-lookup"><span data-stu-id="39cd1-106">This is formed from the concatenation of the RelativeName with the DNS domain used by Azure Traffic Manager.</span></span></param>
        <param name="ttl"><span data-ttu-id="39cd1-107">Ruft ab oder legt die DNS-Gültigkeitsdauer (TTL), in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="39cd1-107">Gets or sets the DNS Time-To-Live (TTL), in seconds.</span></span>  <span data-ttu-id="39cd1-108">Damit wird mitgeteilt, die lokalen DNS-Resolver erkennen und die DNS-Clients, wie lange DNS-Antworten zwischenspeichern, die von diesem Traffic Manager-Profil bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="39cd1-108">This informs the local DNS resolvers and DNS clients how long to cache DNS responses provided by this Traffic Manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="39cd1-109">Initialisiert eine neue Instanz der Klasse DnsConfig an.</span><span class="sxs-lookup"><span data-stu-id="39cd1-109">Initializes a new instance of the DnsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39cd1-110">Ruft ab oder legt den vollqualifizierten Domänennamen (FQDN) des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="39cd1-110">Gets or sets the fully-qualified domain name (FQDN) of the Traffic Manager profile.</span></span>  <span data-ttu-id="39cd1-111">Dies bildet aus der Verkettung von RelativeName mit der DNS-Domäne von Azure Traffic Manager verwendet.</span><span class="sxs-lookup"><span data-stu-id="39cd1-111">This is formed from the concatenation of the RelativeName with the DNS domain used by Azure Traffic Manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeName">
      <MemberSignature Language="C#" Value="public string RelativeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.RelativeName" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeName As String" />
      <MemberSignature Language="F#" Value="member this.RelativeName : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.RelativeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39cd1-112">Ruft ab oder legt den relativen DNS-Namen, die von diesem Traffic Manager-Profil bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="39cd1-112">Gets or sets the relative DNS name provided by this Traffic Manager profile.</span></span>  <span data-ttu-id="39cd1-113">Dieser Wert wird mit dem DNS-Domänennamen kombiniert, der von Azure Traffic Manager zum Erstellen des vollqualifizierten Domänennamens (FQDN) des Profils verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="39cd1-113">This value is combined with the DNS domain name used by Azure Traffic Manager to form the fully-qualified domain name (FQDN) of the profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ttl">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Ttl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Ttl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Ttl" />
      <MemberSignature Language="VB.NET" Value="Public Property Ttl As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Ttl : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Ttl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ttl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39cd1-114">Ruft ab oder legt die DNS-Gültigkeitsdauer (TTL), in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="39cd1-114">Gets or sets the DNS Time-To-Live (TTL), in seconds.</span></span>  <span data-ttu-id="39cd1-115">Damit wird mitgeteilt, die lokalen DNS-Resolver erkennen und die DNS-Clients, wie lange DNS-Antworten zwischenspeichern, die von diesem Traffic Manager-Profil bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="39cd1-115">This informs the local DNS resolvers and DNS clients how long to cache DNS responses provided by this Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>