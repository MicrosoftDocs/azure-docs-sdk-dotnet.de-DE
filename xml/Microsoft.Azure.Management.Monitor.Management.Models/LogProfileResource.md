<Type Name="LogProfileResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource">
  <TypeSignature Language="C#" Value="public class LogProfileResource : Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LogProfileResource extends Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" />
  <TypeSignature Language="VB.NET" Value="Public Class LogProfileResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type LogProfileResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b56f3-101">Die Ressource "Log Profil".</span><span class="sxs-lookup"><span data-stu-id="b56f3-101">The log profile resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogProfileResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-102">Initialisiert eine neue Instanz der LogProfileResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b56f3-102">Initializes a new instance of the LogProfileResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogProfileResource (string location, System.Collections.Generic.IList&lt;string&gt; locations, System.Collections.Generic.IList&lt;string&gt; categories, Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string storageAccountId = null, string serviceBusRuleId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;string&gt; categories, class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string storageAccountId, string serviceBusRuleId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource (location, locations, categories, retentionPolicy, id, name, type, tags, storageAccountId, serviceBusRuleId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="categories" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="serviceBusRuleId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="b56f3-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="b56f3-103">Resource location</span></span></param>
        <param name="locations"><span data-ttu-id="b56f3-104">Die Liste der Regionen, für welche, die Aktivitätsprotokoll Ereignisse gespeichert oder per Stream übertragen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b56f3-104">List of regions for which Activity Log events should be stored or streamed.</span></span> <span data-ttu-id="b56f3-105">Es ist eine durch Trennzeichen getrennte Liste der gültigen ARM Speicherorte einschließlich "globalen" Speicherort.</span><span class="sxs-lookup"><span data-stu-id="b56f3-105">It is a comma separated list of valid ARM locations including the 'global' location.</span></span></param>
        <param name="categories"><span data-ttu-id="b56f3-106">die Kategorien der Protokolle.</span><span class="sxs-lookup"><span data-stu-id="b56f3-106">the categories of the logs.</span></span> <span data-ttu-id="b56f3-107">Diese Kategorien werden als praktisch, den der Benutzer wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="b56f3-107">These categories are created as is convenient to the user.</span></span> <span data-ttu-id="b56f3-108">Einige Werte sind: "Schreiben", "Delete" und/oder "Action".</span><span class="sxs-lookup"><span data-stu-id="b56f3-108">Some values are: 'Write', 'Delete', and/or 'Action.'</span></span></param>
        <param name="retentionPolicy"><span data-ttu-id="b56f3-109">die Aufbewahrungsrichtlinie für die Ereignisse im Protokoll.</span><span class="sxs-lookup"><span data-stu-id="b56f3-109">the retention policy for the events in the log.</span></span></param>
        <param name="id"><span data-ttu-id="b56f3-110">Azure-Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="b56f3-110">Azure resource Id</span></span></param>
        <param name="name"><span data-ttu-id="b56f3-111">Name des Azure-Ressource</span><span class="sxs-lookup"><span data-stu-id="b56f3-111">Azure resource name</span></span></param>
        <param name="type"><span data-ttu-id="b56f3-112">Azure-Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="b56f3-112">Azure resource type</span></span></param>
        <param name="tags"><span data-ttu-id="b56f3-113">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="b56f3-113">Resource tags</span></span></param>
        <param name="storageAccountId"><span data-ttu-id="b56f3-114">die Ressourcen-Id des Speicherkontos an, das Sie zum Senden des Aktivitätsprotokolls möchten.</span><span class="sxs-lookup"><span data-stu-id="b56f3-114">the resource id of the storage account to which you would like to send the Activity Log.</span></span></param>
        <param name="serviceBusRuleId"><span data-ttu-id="b56f3-115">Die Servicebus Regel-ID von der Servicebus-Namespace in dem Sie Event Hubs, die für das Aktivitätsprotokoll streaming erstellt haben möchten.</span><span class="sxs-lookup"><span data-stu-id="b56f3-115">The service bus rule ID of the service bus namespace in which you would like to have Event Hubs created for streaming the Activity Log.</span></span> <span data-ttu-id="b56f3-116">Die Regel-ID im Format ist: "{service Bus-Ressourcen-ID} /authorizationrules/ {Key-Name}".</span><span class="sxs-lookup"><span data-stu-id="b56f3-116">The rule ID is of the format: '{service bus resource ID}/authorizationrules/{key name}'.</span></span></param>
        <summary>
            <span data-ttu-id="b56f3-117">Initialisiert eine neue Instanz der LogProfileResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b56f3-117">Initializes a new instance of the LogProfileResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Categories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Categories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Categories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.Categories" />
      <MemberSignature Language="VB.NET" Value="Public Property Categories As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Categories : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.Categories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.categories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-118">Ruft ab oder legt die Kategorien der Protokolle.</span><span class="sxs-lookup"><span data-stu-id="b56f3-118">Gets or sets the categories of the logs.</span></span> <span data-ttu-id="b56f3-119">Diese Kategorien werden als praktisch, den der Benutzer wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="b56f3-119">These categories are created as is convenient to the user.</span></span> <span data-ttu-id="b56f3-120">Einige Werte sind: "Schreiben", "Delete" und/oder "Action".</span><span class="sxs-lookup"><span data-stu-id="b56f3-120">Some values are: 'Write', 'Delete', and/or 'Action.'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-121">Ruft ab oder legt die Liste der Regionen für die Aktivitätsprotokoll-Ereignisse gespeichert oder per Stream übertragen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b56f3-121">Gets or sets list of regions for which Activity Log events should be stored or streamed.</span></span> <span data-ttu-id="b56f3-122">Es ist eine durch Trennzeichen getrennte Liste der gültigen ARM Speicherorte einschließlich "globalen" Speicherort.</span><span class="sxs-lookup"><span data-stu-id="b56f3-122">It is a comma separated list of valid ARM locations including the 'global' location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-123">Ruft ab oder legt die Aufbewahrungsrichtlinie für die Ereignisse im Protokoll.</span><span class="sxs-lookup"><span data-stu-id="b56f3-123">Gets or sets the retention policy for the events in the log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusRuleId">
      <MemberSignature Language="C#" Value="public string ServiceBusRuleId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.ServiceBusRuleId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusRuleId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusRuleId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.ServiceBusRuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusRuleId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-124">Ermittelt oder definiert die Servicebus-Regel-ID von der Servicebus-Namespace in dem Sie Event Hubs, die für das Aktivitätsprotokoll streaming erstellt haben möchten.</span><span class="sxs-lookup"><span data-stu-id="b56f3-124">Gets or sets the service bus rule ID of the service bus namespace in which you would like to have Event Hubs created for streaming the Activity Log.</span></span> <span data-ttu-id="b56f3-125">Die Regel-ID im Format ist: "{service Bus-Ressourcen-ID} /authorizationrules/ {Key-Name}".</span><span class="sxs-lookup"><span data-stu-id="b56f3-125">The rule ID is of the format: '{service bus resource ID}/authorizationrules/{key name}'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-126">Ruft ab oder legt die Ressourcen-Id des Speicherkontos an, das Sie zum Senden des Aktivitätsprotokolls möchten.</span><span class="sxs-lookup"><span data-stu-id="b56f3-126">Gets or sets the resource id of the storage account to which you would like to send the Activity Log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="logProfileResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b56f3-127">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b56f3-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b56f3-128">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b56f3-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>