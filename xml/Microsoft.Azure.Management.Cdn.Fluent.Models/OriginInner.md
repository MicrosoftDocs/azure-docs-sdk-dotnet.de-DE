<Type Name="OriginInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner">
  <TypeSignature Language="C#" Value="public class OriginInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OriginInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner" />
  <TypeSignature Language="VB.NET" Value="Public Class OriginInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type OriginInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="47678-101">CDN Ursprung ist die Quelle des Inhalts über CDN übermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="47678-101">CDN origin is the source of the content being delivered via CDN.</span></span> <span data-ttu-id="47678-102">Bei edgeknoten, die von einem Endpunkt dargestellt nicht den angeforderten Inhalt zwischengespeichert haben, versuchen sie es aus einer oder mehreren der konfigurierten Ursprünge abzurufen.</span><span class="sxs-lookup"><span data-stu-id="47678-102">When the edge nodes represented by an endpoint do not have the requested content cached, they attempt to fetch it from one or more of the configured origins.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OriginInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="47678-103">Initialisiert eine neue Instanz der OriginInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="47678-103">Initializes a new instance of the OriginInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OriginInner (string hostName, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; httpPort = null, Nullable&lt;int&gt; httpsPort = null, string resourceState = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; httpPort, valuetype System.Nullable`1&lt;int32&gt; httpsPort, string resourceState, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional httpPort As Nullable(Of Integer) = null, Optional httpsPort As Nullable(Of Integer) = null, Optional resourceState As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner (hostName, location, id, name, type, tags, httpPort, httpsPort, resourceState, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="httpPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="httpsPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resourceState" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="47678-104">Die Adresse des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="47678-104">The address of the origin.</span></span> <span data-ttu-id="47678-105">Domänennamen, IPv4-Adressen und IPv6-Adressen werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="47678-105">Domain names, IPv4 addresses, and IPv6 addresses are supported.</span></span></param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="httpPort"><span data-ttu-id="47678-106">Der Wert des HTTP-Port.</span><span class="sxs-lookup"><span data-stu-id="47678-106">The value of the HTTP port.</span></span> <span data-ttu-id="47678-107">Muss zwischen 1 und 65535 liegen.</span><span class="sxs-lookup"><span data-stu-id="47678-107">Must be between 1 and 65535.</span></span></param>
        <param name="httpsPort"><span data-ttu-id="47678-108">Der Wert der Https-Port.</span><span class="sxs-lookup"><span data-stu-id="47678-108">The value of the https port.</span></span> <span data-ttu-id="47678-109">Muss zwischen 1 und 65535 liegen.</span><span class="sxs-lookup"><span data-stu-id="47678-109">Must be between 1 and 65535.</span></span></param>
        <param name="resourceState"><span data-ttu-id="47678-110">Den Ressourcenstatus des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="47678-110">Resource status of the origin.</span></span> <span data-ttu-id="47678-111">Folgende Werte sind möglich: 'Erstellen', 'Active', 'Löschen'</span><span class="sxs-lookup"><span data-stu-id="47678-111">Possible values include: 'Creating', 'Active', 'Deleting'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="47678-112">Der Bereitstellungsstatus des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="47678-112">Provisioning status of the origin.</span></span></param>
        <summary>
            <span data-ttu-id="47678-113">Initialisiert eine neue Instanz der OriginInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="47678-113">Initializes a new instance of the OriginInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47678-114">Ruft ab oder legt die Adresse des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="47678-114">Gets or sets the address of the origin.</span></span> <span data-ttu-id="47678-115">Domänennamen, IPv4-Adressen und IPv6-Adressen werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="47678-115">Domain names, IPv4 addresses, and IPv6 addresses are supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; HttpPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; HttpPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.HttpPort" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.HttpPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.HttpPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47678-116">Ruft ab oder legt den Wert des HTTP-Port.</span><span class="sxs-lookup"><span data-stu-id="47678-116">Gets or sets the value of the HTTP port.</span></span> <span data-ttu-id="47678-117">Muss liegen zwischen 1 und</span><span class="sxs-lookup"><span data-stu-id="47678-117">Must be between 1 and</span></span>
            65535.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; HttpsPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; HttpsPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.HttpsPort" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpsPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.HttpsPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.HttpsPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpsPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47678-118">Ruft ab oder legt den Wert für die Https-Port.</span><span class="sxs-lookup"><span data-stu-id="47678-118">Gets or sets the value of the https port.</span></span> <span data-ttu-id="47678-119">Muss liegen zwischen 1 und</span><span class="sxs-lookup"><span data-stu-id="47678-119">Must be between 1 and</span></span>
            65535.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47678-120">Status des Ursprungs ruft bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="47678-120">Gets provisioning status of the origin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47678-121">Ruft den Ursprung Ressourcenstatus ab.</span><span class="sxs-lookup"><span data-stu-id="47678-121">Gets resource status of the origin.</span></span> <span data-ttu-id="47678-122">Folgende Werte sind möglich: 'Erstellen', 'Active', 'Löschen'</span><span class="sxs-lookup"><span data-stu-id="47678-122">Possible values include: 'Creating', 'Active', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="originInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="47678-123">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="47678-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47678-124">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="47678-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>