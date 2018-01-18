<Type Name="Registry" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Registry">
  <TypeSignature Language="C#" Value="public class Registry : Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Registry extends Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
  <TypeSignature Language="VB.NET" Value="Public Class Registry&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Registry = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerRegistry.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2eabe-101">Ein Objekt, das eine containerregistrierung darstellt.</span><span class="sxs-lookup"><span data-stu-id="2eabe-101">An object that represents a container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Registry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-102">Initialisiert eine neue Instanz der Klasse Registrierung.</span><span class="sxs-lookup"><span data-stu-id="2eabe-102">Initializes a new instance of the Registry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Registry (string location, Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string loginServer = null, Nullable&lt;DateTime&gt; creationDate = null, string provisioningState = null, Microsoft.Azure.Management.ContainerRegistry.Models.Status status = null, Nullable&lt;bool&gt; adminUserEnabled = null, Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string loginServer, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, string provisioningState, class Microsoft.Azure.Management.ContainerRegistry.Models.Status status, valuetype System.Nullable`1&lt;bool&gt; adminUserEnabled, class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.#ctor(System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Status,System.Nullable{System.Boolean},Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Registry : string * Microsoft.Azure.Management.ContainerRegistry.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.ContainerRegistry.Models.Status * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Registry (location, sku, id, name, type, tags, loginServer, creationDate, provisioningState, status, adminUserEnabled, storageAccount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="loginServer" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Status" />
        <Parameter Name="adminUserEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="2eabe-103">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2eabe-103">The location of the resource.</span></span> <span data-ttu-id="2eabe-104">Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="2eabe-104">This cannot be changed after the resource is created.</span></span></param>
        <param name="sku"><span data-ttu-id="2eabe-105">Die SKU der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="2eabe-105">The SKU of the container registry.</span></span></param>
        <param name="id"><span data-ttu-id="2eabe-106">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="2eabe-106">The resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="2eabe-107">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2eabe-107">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="2eabe-108">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2eabe-108">The type of the resource.</span></span></param>
        <param name="tags"><span data-ttu-id="2eabe-109">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2eabe-109">The tags of the resource.</span></span></param>
        <param name="loginServer"><span data-ttu-id="2eabe-110">Die URL, die sich in der containerregistrierung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="2eabe-110">The URL that can be used to log into the container registry.</span></span></param>
        <param name="creationDate"><span data-ttu-id="2eabe-111">Das Erstellungsdatum der containerregistrierung im ISO8601-Format.</span><span class="sxs-lookup"><span data-stu-id="2eabe-111">The creation date of the container registry in ISO8601 format.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="2eabe-112">Der Bereitstellungsstatus der containerregistrierung zu dem Zeitpunkt, zu der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="2eabe-112">The provisioning state of the container registry at the time the operation was called.</span></span> <span data-ttu-id="2eabe-113">Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="2eabe-113">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <param name="status"><span data-ttu-id="2eabe-114">Der Status der containerregistrierung zum Zeitpunkt der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="2eabe-114">The status of the container registry at the time the operation was called.</span></span></param>
        <param name="adminUserEnabled"><span data-ttu-id="2eabe-115">Der Wert, der angibt, ob die adminbenutzer aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="2eabe-115">The value that indicates whether the admin user is enabled.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="2eabe-116">Die Eigenschaften des Speicherkontos für die containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="2eabe-116">The properties of the storage account for the container registry.</span></span> <span data-ttu-id="2eabe-117">Gilt nur für klassische SKU.</span><span class="sxs-lookup"><span data-stu-id="2eabe-117">Only applicable to Classic SKU.</span></span></param>
        <summary>
            <span data-ttu-id="2eabe-118">Initialisiert eine neue Instanz der Klasse Registrierung.</span><span class="sxs-lookup"><span data-stu-id="2eabe-118">Initializes a new instance of the Registry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdminUserEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdminUserEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.AdminUserEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdminUserEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.AdminUserEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminUserEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-119">Ruft ab oder legt den Wert, der angibt, ob die adminbenutzer aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="2eabe-119">Gets or sets the value that indicates whether the admin user is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-120">Ruft das Erstellungsdatum der containerregistrierung im ISO8601-Format ab.</span><span class="sxs-lookup"><span data-stu-id="2eabe-120">Gets the creation date of the container registry in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginServer">
      <MemberSignature Language="C#" Value="public string LoginServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.LoginServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoginServer As String" />
      <MemberSignature Language="F#" Value="member this.LoginServer : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.LoginServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loginServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-121">Ruft die URL, die zum Anmelden verwendet werden kann, in der containerregistrierung ab.</span><span class="sxs-lookup"><span data-stu-id="2eabe-121">Gets the URL that can be used to log into the container registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2eabe-122">Ruft den Bereitstellungsstatus der der containerregistrierung zu dem Zeitpunkt, der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="2eabe-122">Gets the provisioning state of the container registry at the time the operation was called.</span></span> <span data-ttu-id="2eabe-123">Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="2eabe-123">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ContainerRegistry.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-124">Abrufen oder festlegen die SKU der containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="2eabe-124">Gets or sets the SKU of the container registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Status Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Status Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Status" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ContainerRegistry.Models.Status" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Status</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-125">Ruft den Status der containerregistrierung ab, zu dem Zeitpunkt, der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="2eabe-125">Gets the status of the container registry at the time the operation was called.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccountProperties" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-126">Ruft ab oder legt die Eigenschaften des Speicherkontos für die containerregistrierung fest.</span><span class="sxs-lookup"><span data-stu-id="2eabe-126">Gets or sets the properties of the storage account for the container registry.</span></span> <span data-ttu-id="2eabe-127">Gilt nur für klassische SKU.</span><span class="sxs-lookup"><span data-stu-id="2eabe-127">Only applicable to Classic SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="registry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2eabe-128">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2eabe-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2eabe-129">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2eabe-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>