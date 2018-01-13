<Type Name="Webhook" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook">
  <TypeSignature Language="C#" Value="public class Webhook : Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Webhook extends Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" />
  <TypeSignature Language="VB.NET" Value="Public Class Webhook&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Webhook = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="8129c-101">Ein Objekt, das einen Webhook für die containerregistrierung eines darstellt.</span><span class="sxs-lookup"><span data-stu-id="8129c-101">An object that represents a webhook for a container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Webhook ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8129c-102">Initialisiert eine neue Instanz der Klasse Webhook.</span><span class="sxs-lookup"><span data-stu-id="8129c-102">Initializes a new instance of the Webhook class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Webhook (string location, System.Collections.Generic.IList&lt;string&gt; actions, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string status = null, string scope = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;string&gt; actions, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string status, string scope, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, actions As IList(Of String), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional status As String = null, Optional scope As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Webhook : string * System.Collections.Generic.IList&lt;string&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Webhook (location, actions, id, name, type, tags, status, scope, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="8129c-103">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8129c-103">The location of the resource.</span></span> <span data-ttu-id="8129c-104">Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="8129c-104">This cannot be changed after the resource is created.</span></span></param>
        <param name="actions"><span data-ttu-id="8129c-105">Die Liste der Aktionen, die Auslösen des webhooks, um Benachrichtigungen zu senden.</span><span class="sxs-lookup"><span data-stu-id="8129c-105">The list of actions that trigger the webhook to post notifications.</span></span></param>
        <param name="id"><span data-ttu-id="8129c-106">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="8129c-106">The resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="8129c-107">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8129c-107">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="8129c-108">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8129c-108">The type of the resource.</span></span></param>
        <param name="tags"><span data-ttu-id="8129c-109">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8129c-109">The tags of the resource.</span></span></param>
        <param name="status"><span data-ttu-id="8129c-110">Der Status des webhooks, die zum Zeitpunkt der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="8129c-110">The status of the webhook at the time the operation was called.</span></span> <span data-ttu-id="8129c-111">Folgende Werte sind möglich: "enabled", "disabled"</span><span class="sxs-lookup"><span data-stu-id="8129c-111">Possible values include: 'enabled', 'disabled'</span></span></param>
        <param name="scope"><span data-ttu-id="8129c-112">Der Bereich des Repositorys, auf dem das Ereignis ausgelöst werden kann.</span><span class="sxs-lookup"><span data-stu-id="8129c-112">The scope of repositories where the event can be triggered.</span></span> <span data-ttu-id="8129c-113">Z. B. "Foo: \*' bedeutet, dass Ereignisse für alle Tags unter Repository"Foo".</span><span class="sxs-lookup"><span data-stu-id="8129c-113">For example, 'foo:\*' means events for all tags under repository 'foo'.</span></span> <span data-ttu-id="8129c-114">"Foo:bar" bedeutet, dass Ereignisse bei "Foo:bar" nur.</span><span class="sxs-lookup"><span data-stu-id="8129c-114">'foo:bar' means events for 'foo:bar' only.</span></span> <span data-ttu-id="8129c-115">"Foo" entspricht "Foo:latest".</span><span class="sxs-lookup"><span data-stu-id="8129c-115">'foo' is equivalent to 'foo:latest'.</span></span> <span data-ttu-id="8129c-116">Alle Ereignisse "leer" bedeutet.</span><span class="sxs-lookup"><span data-stu-id="8129c-116">Empty means all events.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="8129c-117">Der Bereitstellungsstatus des des webhooks zur Zeit, die der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="8129c-117">The provisioning state of the webhook at the time the operation was called.</span></span> <span data-ttu-id="8129c-118">Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="8129c-118">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <summary>
            <span data-ttu-id="8129c-119">Initialisiert eine neue Instanz der Klasse Webhook.</span><span class="sxs-lookup"><span data-stu-id="8129c-119">Initializes a new instance of the Webhook class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.actions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8129c-120">Ruft ab oder legt die Liste der Aktionen, die Auslösen des webhooks, um Benachrichtigungen zu senden.</span><span class="sxs-lookup"><span data-stu-id="8129c-120">Gets or sets the list of actions that trigger the webhook to post notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.ProvisioningState" />
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
            <span data-ttu-id="8129c-121">Ruft den Bereitstellungsstatus der Webhook zum Zeitpunkt der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="8129c-121">Gets the provisioning state of the webhook at the time the operation was called.</span></span> <span data-ttu-id="8129c-122">Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="8129c-122">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8129c-123">Ruft ab oder legt den Bereich der Repositorys, auf dem das Ereignis ausgelöst werden kann.</span><span class="sxs-lookup"><span data-stu-id="8129c-123">Gets or sets the scope of repositories where the event can be triggered.</span></span> <span data-ttu-id="8129c-124">Z. B. "Foo: \*' bedeutet, dass Ereignisse für alle Tags unter Repository"Foo".</span><span class="sxs-lookup"><span data-stu-id="8129c-124">For example, 'foo:\*' means events for all tags under repository 'foo'.</span></span> <span data-ttu-id="8129c-125">"Foo:bar" bedeutet, dass Ereignisse bei "Foo:bar" nur.</span><span class="sxs-lookup"><span data-stu-id="8129c-125">'foo:bar' means events for 'foo:bar' only.</span></span> <span data-ttu-id="8129c-126">"Foo" entspricht "Foo:latest".</span><span class="sxs-lookup"><span data-stu-id="8129c-126">'foo' is equivalent to 'foo:latest'.</span></span> <span data-ttu-id="8129c-127">Alle Ereignisse "leer" bedeutet.</span><span class="sxs-lookup"><span data-stu-id="8129c-127">Empty means all events.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Status" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8129c-128">Ruft ab oder legt den Status des webhooks fest, die zum Zeitpunkt der Vorgang aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="8129c-128">Gets or sets the status of the webhook at the time the operation was called.</span></span> <span data-ttu-id="8129c-129">Folgende Werte sind möglich: "enabled", "disabled"</span><span class="sxs-lookup"><span data-stu-id="8129c-129">Possible values include: 'enabled', 'disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Webhook.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webhook.Validate " />
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
            <span data-ttu-id="8129c-130">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8129c-130">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8129c-131">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8129c-131">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>