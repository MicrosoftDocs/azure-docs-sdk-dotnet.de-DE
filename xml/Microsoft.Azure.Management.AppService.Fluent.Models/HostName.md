<Type Name="HostName" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.HostName">
  <TypeSignature Language="C#" Value="public class HostName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostName extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.HostName" />
  <TypeSignature Language="VB.NET" Value="Public Class HostName" />
  <TypeSignature Language="F#" Value="type HostName = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7209a-101">Details der einen Hostnamen aus einer Domäne abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="7209a-101">Details of a hostname derived from a domain.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7209a-102">Initialisiert eine neue Instanz der Klasse Hostnamen an.</span><span class="sxs-lookup"><span data-stu-id="7209a-102">Initializes a new instance of the HostName class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostName (string name = null, System.Collections.Generic.IList&lt;string&gt; siteNames = null, string azureResourceName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; azureResourceType = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; hostNameType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; siteNames, string azureResourceName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; azureResourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; hostNameType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional siteNames As IList(Of String) = null, Optional azureResourceName As String = null, Optional azureResourceType As Nullable(Of AzureResourceType) = null, Optional customHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType) = null, Optional hostNameType As Nullable(Of HostNameType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.HostName : string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.HostName" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.HostName (name, siteNames, azureResourceName, azureResourceType, customHostNameDnsRecordType, hostNameType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="siteNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="azureResourceName" Type="System.String" />
        <Parameter Name="azureResourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt;" />
        <Parameter Name="customHostNameDnsRecordType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt;" />
        <Parameter Name="hostNameType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7209a-103">Der Name des Hostnamens.</span><span class="sxs-lookup"><span data-stu-id="7209a-103">Name of the hostname.</span></span></param>
        <param name="siteNames"><span data-ttu-id="7209a-104">Liste von apps, denen der Hostname zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="7209a-104">List of apps the hostname is assigned to.</span></span>
            <span data-ttu-id="7209a-105">Diese Liste wird mehr als eine app haben, nur, wenn der Hostname zu einer Traffic Manager verweist.</span><span class="sxs-lookup"><span data-stu-id="7209a-105">This list will have more than one app only if the hostname is pointing to a Traffic Manager.</span></span></param>
        <param name="azureResourceName"><span data-ttu-id="7209a-106">Name des Azure-Ressource dem Hostnamen zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="7209a-106">Name of the Azure resource the hostname is assigned to.</span></span> <span data-ttu-id="7209a-107">Wenn sie ein Traffic Manager zugewiesen ist, wird er mit den Namen des Traffic Manager kann wird andernfalls es der app-Name sein.</span><span class="sxs-lookup"><span data-stu-id="7209a-107">If it is assigned to a Traffic Manager then it will be the Traffic Manager name otherwise it will be the app name.</span></span></param>
        <param name="azureResourceType"><span data-ttu-id="7209a-108">Typ des Azure-Ressource dem Hostnamen zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="7209a-108">Type of the Azure resource the hostname is assigned to.</span></span> <span data-ttu-id="7209a-109">Folgende Werte sind möglich: "Website", "TrafficManager"</span><span class="sxs-lookup"><span data-stu-id="7209a-109">Possible values include: 'Website', 'TrafficManager'</span></span></param>
        <param name="customHostNameDnsRecordType"><span data-ttu-id="7209a-110">Geben Sie den DNS-Eintrag.</span><span class="sxs-lookup"><span data-stu-id="7209a-110">Type of the DNS record.</span></span>
            <span data-ttu-id="7209a-111">Folgende Werte sind möglich: "CName", "A"</span><span class="sxs-lookup"><span data-stu-id="7209a-111">Possible values include: 'CName', 'A'</span></span></param>
        <param name="hostNameType"><span data-ttu-id="7209a-112">Der Typ des Hostnamens.</span><span class="sxs-lookup"><span data-stu-id="7209a-112">Type of the hostname.</span></span> <span data-ttu-id="7209a-113">Folgende Werte sind möglich: "Überprüft", "Verwaltet"</span><span class="sxs-lookup"><span data-stu-id="7209a-113">Possible values include: 'Verified', 'Managed'</span></span></param>
        <summary>
            <span data-ttu-id="7209a-114">Initialisiert eine neue Instanz der Klasse Hostnamen an.</span><span class="sxs-lookup"><span data-stu-id="7209a-114">Initializes a new instance of the HostName class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceName">
      <MemberSignature Language="C#" Value="public string AzureResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AzureResourceName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureResourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7209a-115">Ruft ab, oder legt ihn fest Name des Azure-Ressource, der der Hostnamen zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="7209a-115">Gets or sets name of the Azure resource the hostname is assigned to.</span></span> <span data-ttu-id="7209a-116">Wenn sie ein Traffic Manager zugewiesen ist, wird er mit den Namen des Traffic Manager kann wird andernfalls es der app-Name sein.</span><span class="sxs-lookup"><span data-stu-id="7209a-116">If it is assigned to a Traffic Manager then it will be the Traffic Manager name otherwise it will be the app name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; AzureResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; AzureResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceType As Nullable(Of AzureResourceType)" />
      <MemberSignature Language="F#" Value="member this.AzureResourceType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureResourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7209a-117">Ruft ab oder legt ihn fest der Azure-Ressource, der der Hostnamen zugewiesen ist.</span><span class="sxs-lookup"><span data-stu-id="7209a-117">Gets or sets type of the Azure resource the hostname is assigned to.</span></span> <span data-ttu-id="7209a-118">Folgende Werte sind möglich: "Website", "TrafficManager"</span><span class="sxs-lookup"><span data-stu-id="7209a-118">Possible values include: 'Website', 'TrafficManager'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHostNameDnsRecordType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.CustomHostNameDnsRecordType" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType)" />
      <MemberSignature Language="F#" Value="member this.CustomHostNameDnsRecordType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.CustomHostNameDnsRecordType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customHostNameDnsRecordType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7209a-119">Ruft ab oder legt ihn fest den DNS-Eintrag.</span><span class="sxs-lookup"><span data-stu-id="7209a-119">Gets or sets type of the DNS record.</span></span> <span data-ttu-id="7209a-120">Folgende Werte sind möglich: "CName", "A"</span><span class="sxs-lookup"><span data-stu-id="7209a-120">Possible values include: 'CName', 'A'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; HostNameType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; HostNameType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.HostNameType" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameType As Nullable(Of HostNameType)" />
      <MemberSignature Language="F#" Value="member this.HostNameType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.HostNameType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostNameType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7209a-121">Ruft ab oder legt ihn fest des Hostnamens.</span><span class="sxs-lookup"><span data-stu-id="7209a-121">Gets or sets type of the hostname.</span></span> <span data-ttu-id="7209a-122">Folgende Werte sind möglich: "Überprüft", "Verwaltet"</span><span class="sxs-lookup"><span data-stu-id="7209a-122">Possible values include: 'Verified', 'Managed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="7209a-123">Ruft ab oder legt den Namen des Hostnamens fest.</span><span class="sxs-lookup"><span data-stu-id="7209a-123">Gets or sets name of the hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SiteNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SiteNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.SiteNames" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SiteNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.SiteNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="siteNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7209a-124">Ruft ab, oder legt ihn fest Liste von apps, denen der Hostname zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="7209a-124">Gets or sets list of apps the hostname is assigned to.</span></span> <span data-ttu-id="7209a-125">Diese Liste wird mehr als eine app haben, nur, wenn der Hostname zu einer Traffic Manager verweist.</span><span class="sxs-lookup"><span data-stu-id="7209a-125">This list will have more than one app only if the hostname is pointing to a Traffic Manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>