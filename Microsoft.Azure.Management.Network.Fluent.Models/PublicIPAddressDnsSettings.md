<Type Name="PublicIPAddressDnsSettings" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings">
  <TypeSignature Language="C#" Value="public class PublicIPAddressDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PublicIPAddressDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PublicIPAddressDnsSettings" />
  <TypeSignature Language="F#" Value="type PublicIPAddressDnsSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a54ff-101">Enthält den DNS-Eintrag die öffentliche IP-Adresse zugeordnete FQDN</span><span class="sxs-lookup"><span data-stu-id="a54ff-101">Contains FQDN of the DNS record associated with the public IP address</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddressDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a54ff-102">Initialisiert eine neue Instanz der PublicIPAddressDnsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a54ff-102">Initializes a new instance of the PublicIPAddressDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddressDnsSettings (string domainNameLabel = null, string fqdn = null, string reverseFqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string domainNameLabel, string fqdn, string reverseFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional domainNameLabel As String = null, Optional fqdn As String = null, Optional reverseFqdn As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings (domainNameLabel, fqdn, reverseFqdn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="domainNameLabel" Type="System.String" />
        <Parameter Name="fqdn" Type="System.String" />
        <Parameter Name="reverseFqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainNameLabel"><span data-ttu-id="a54ff-103">Ruft ab oder legt die domänennamenbezeichnung. Die Verkettung der domänennamenbezeichnung und der regionalisierten DNS-Zone bilden zusammen den vollqualifizierten Domänennamen der öffentlichen IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a54ff-103">Gets or sets the Domain name label.The concatenation of the domain name label and the regionalized DNS zone make up the fully qualified domain name associated with the public IP address.</span></span> <span data-ttu-id="a54ff-104">Wenn eine domänennamenbezeichnung angegeben ist, wird ein A-DNS-Datensatz für die öffentliche IP-Adresse im Microsoft Azure-DNS-System erstellt.</span><span class="sxs-lookup"><span data-stu-id="a54ff-104">If a domain name label is specified, an A DNS record is created for the public IP in the Microsoft Azure DNS system.</span></span></param>
        <param name="fqdn"><span data-ttu-id="a54ff-105">Ruft den vollqualifizierten Domänennamen, vollständig qualifizierten Domänennamen des A-DNS-Datensatzes der öffentlichen IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a54ff-105">Gets the FQDN, Fully qualified domain name of the A DNS record associated with the public IP.</span></span> <span data-ttu-id="a54ff-106">Dies ist die Verkettung von DomainNameLabel und der regionalisierten DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="a54ff-106">This is the concatenation of the domainNameLabel and the regionalized DNS zone.</span></span></param>
        <param name="reverseFqdn"><span data-ttu-id="a54ff-107">Ruft ab oder legt den Reverse-FQDN.</span><span class="sxs-lookup"><span data-stu-id="a54ff-107">Gets or Sets the Reverse FQDN.</span></span> <span data-ttu-id="a54ff-108">Ein Benutzer sichtbare, vollständig qualifizierter Domänenname, der in diese öffentliche IP-Adresse aufgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="a54ff-108">A user-visible, fully qualified domain name that resolves to this public IP address.</span></span> <span data-ttu-id="a54ff-109">Wenn ReverseFqdn angegeben ist, wird ein PTR DNS-Datensatz auf den reverse-FQDN von der IP-Adresse in der in-addr.arpa-Domäne erstellt.</span><span class="sxs-lookup"><span data-stu-id="a54ff-109">If the reverseFqdn is specified, then a PTR DNS record is created pointing from the IP address in the in-addr.arpa domain to the reverse FQDN.</span></span> </param>
        <summary>
            <span data-ttu-id="a54ff-110">Initialisiert eine neue Instanz der PublicIPAddressDnsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a54ff-110">Initializes a new instance of the PublicIPAddressDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainNameLabel">
      <MemberSignature Language="C#" Value="public string DomainNameLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.DomainNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.DomainNameLabel : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.DomainNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="domainNameLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54ff-111">Ruft ab oder legt die domänennamenbezeichnung. Die Verkettung der domänennamenbezeichnung und der regionalisierten DNS-Zone bilden zusammen den vollqualifizierten Domänennamen der öffentlichen IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a54ff-111">Gets or sets the Domain name label.The concatenation of the domain name label and the regionalized DNS zone make up the fully qualified domain name associated with the public IP address.</span></span> <span data-ttu-id="a54ff-112">Wenn eine domänennamenbezeichnung angegeben ist, wird ein A-DNS-Datensatz für die öffentliche IP-Adresse im Microsoft Azure-DNS-System erstellt.</span><span class="sxs-lookup"><span data-stu-id="a54ff-112">If a domain name label is specified, an A DNS record is created for the public IP in the Microsoft Azure DNS system.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="a54ff-113">Ruft den vollqualifizierten Domänennamen, vollständig qualifizierten Domänennamen des A-DNS-Datensatzes der öffentlichen IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a54ff-113">Gets the FQDN, Fully qualified domain name of the A DNS record associated with the public IP.</span></span> <span data-ttu-id="a54ff-114">Dies ist die Verkettung von DomainNameLabel und der regionalisierten DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="a54ff-114">This is the concatenation of the domainNameLabel and the regionalized DNS zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseFqdn">
      <MemberSignature Language="C#" Value="public string ReverseFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReverseFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.ReverseFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseFqdn As String" />
      <MemberSignature Language="F#" Value="member this.ReverseFqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.ReverseFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reverseFqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54ff-115">Ruft ab oder legt den Reverse-FQDN.</span><span class="sxs-lookup"><span data-stu-id="a54ff-115">Gets or Sets the Reverse FQDN.</span></span> <span data-ttu-id="a54ff-116">Ein Benutzer sichtbare, vollständig qualifizierter Domänenname, der in diese öffentliche IP-Adresse aufgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="a54ff-116">A user-visible, fully qualified domain name that resolves to this public IP address.</span></span> <span data-ttu-id="a54ff-117">Wenn ReverseFqdn angegeben ist, wird ein PTR DNS-Datensatz auf den reverse-FQDN von der IP-Adresse in der in-addr.arpa-Domäne erstellt.</span><span class="sxs-lookup"><span data-stu-id="a54ff-117">If the reverseFqdn is specified, then a PTR DNS record is created pointing from the IP address in the in-addr.arpa domain to the reverse FQDN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>