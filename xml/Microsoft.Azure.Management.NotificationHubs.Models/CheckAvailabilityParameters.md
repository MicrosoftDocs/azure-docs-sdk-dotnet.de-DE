<Type Name="CheckAvailabilityParameters" FullName="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters">
  <TypeSignature Language="C#" Value="public class CheckAvailabilityParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckAvailabilityParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckAvailabilityParameters" />
  <TypeSignature Language="F#" Value="type CheckAvailabilityParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5b5a0-101">Um die Verfügbarkeit prüfen für Namespace und NotificationHubs eingegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="5b5a0-101">Parameters supplied to the Check Name Availability for Namespace and NotificationHubs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckAvailabilityParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b5a0-102">Initialisiert eine neue Instanz der CheckAvailabilityParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b5a0-102">Initializes a new instance of the CheckAvailabilityParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckAvailabilityParameters (string name, string location, string id = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, Nullable&lt;bool&gt; isAvailiable = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string location, string id, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; isAvailiable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters (name, location, id, type, tags, sku, isAvailiable)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="isAvailiable" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5b5a0-103">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="5b5a0-103">Resource name</span></span></param>
        <param name="location"><span data-ttu-id="5b5a0-104">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="5b5a0-104">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="5b5a0-105">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="5b5a0-105">Resource Id</span></span></param>
        <param name="type"><span data-ttu-id="5b5a0-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="5b5a0-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="5b5a0-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="5b5a0-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="5b5a0-108">Die Sku des erstellten namespace</span><span class="sxs-lookup"><span data-stu-id="5b5a0-108">The sku of the created namespace</span></span></param>
        <param name="isAvailiable"><span data-ttu-id="5b5a0-109">"True", wenn der Name verfügbar ist, und kann zum Erstellen von neuen Namespace/NotificationHub verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5b5a0-109">True if the name is available and can be used to create new Namespace/NotificationHub.</span></span> <span data-ttu-id="5b5a0-110">Andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5b5a0-110">Otherwise false.</span></span></param>
        <summary>
            <span data-ttu-id="5b5a0-111">Initialisiert eine neue Instanz der CheckAvailabilityParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b5a0-111">Initializes a new instance of the CheckAvailabilityParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b5a0-112">Ruft die Ressourcen-Id ab</span><span class="sxs-lookup"><span data-stu-id="5b5a0-112">Gets resource Id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAvailiable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAvailiable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAvailiable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.IsAvailiable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAvailiable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAvailiable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.IsAvailiable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAvailiable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b5a0-113">Ruft ab oder legt "true", wenn der Name verfügbar ist und kann zum Erstellen von neuen Namespace/NotificationHub verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5b5a0-113">Gets or sets true if the name is available and can be used to create new Namespace/NotificationHub.</span></span> <span data-ttu-id="5b5a0-114">Andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5b5a0-114">Otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5b5a0-115">Ruft ab oder legt ihn fest Ressourcenspeicherort</span><span class="sxs-lookup"><span data-stu-id="5b5a0-115">Gets or sets resource location</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5b5a0-116">Ruft ab oder legt ihn fest-Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="5b5a0-116">Gets or sets resource name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.NotificationHubs.Models.Sku with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b5a0-117">Ruft ab oder legt die Sku des erstellten namespace</span><span class="sxs-lookup"><span data-stu-id="5b5a0-117">Gets or sets the sku of the created namespace</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b5a0-118">Ruft ab oder legt ihn fest Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="5b5a0-118">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5b5a0-119">Ruft Ressourcentyp ab</span><span class="sxs-lookup"><span data-stu-id="5b5a0-119">Gets resource type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>