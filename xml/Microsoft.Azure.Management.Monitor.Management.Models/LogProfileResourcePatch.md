<Type Name="LogProfileResourcePatch" FullName="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch">
  <TypeSignature Language="C#" Value="public class LogProfileResourcePatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LogProfileResourcePatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" />
  <TypeSignature Language="VB.NET" Value="Public Class LogProfileResourcePatch" />
  <TypeSignature Language="F#" Value="type LogProfileResourcePatch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1fac0-101">Die Ressource "Log Profil" für Update-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="1fac0-101">The log profile resource for patch operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogProfileResourcePatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.#ctor" />
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
            <span data-ttu-id="1fac0-102">Initialisiert eine neue Instanz der LogProfileResourcePatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1fac0-102">Initializes a new instance of the LogProfileResourcePatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogProfileResourcePatch (System.Collections.Generic.IList&lt;string&gt; locations, System.Collections.Generic.IList&lt;string&gt; categories, Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string storageAccountId = null, string serviceBusRuleId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;string&gt; categories, class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy retentionPolicy, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string storageAccountId, string serviceBusRuleId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch (locations, categories, retentionPolicy, tags, storageAccountId, serviceBusRuleId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="categories" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="serviceBusRuleId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="locations"><span data-ttu-id="1fac0-103">Die Liste der Regionen, für welche, die Aktivitätsprotokoll Ereignisse gespeichert oder per Stream übertragen werden soll.</span><span class="sxs-lookup"><span data-stu-id="1fac0-103">List of regions for which Activity Log events should be stored or streamed.</span></span> <span data-ttu-id="1fac0-104">Es ist eine durch Trennzeichen getrennte Liste der gültigen ARM Speicherorte einschließlich "globalen" Speicherort.</span><span class="sxs-lookup"><span data-stu-id="1fac0-104">It is a comma separated list of valid ARM locations including the 'global' location.</span></span></param>
        <param name="categories"><span data-ttu-id="1fac0-105">die Kategorien der Protokolle.</span><span class="sxs-lookup"><span data-stu-id="1fac0-105">the categories of the logs.</span></span> <span data-ttu-id="1fac0-106">Diese Kategorien werden als praktisch, den der Benutzer wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="1fac0-106">These categories are created as is convenient to the user.</span></span> <span data-ttu-id="1fac0-107">Einige Werte sind: "Schreiben", "Delete" und/oder "Action".</span><span class="sxs-lookup"><span data-stu-id="1fac0-107">Some values are: 'Write', 'Delete', and/or 'Action.'</span></span></param>
        <param name="retentionPolicy"><span data-ttu-id="1fac0-108">die Aufbewahrungsrichtlinie für die Ereignisse im Protokoll.</span><span class="sxs-lookup"><span data-stu-id="1fac0-108">the retention policy for the events in the log.</span></span></param>
        <param name="tags"><span data-ttu-id="1fac0-109">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="1fac0-109">Resource tags</span></span></param>
        <param name="storageAccountId"><span data-ttu-id="1fac0-110">die Ressourcen-Id des Speicherkontos an, das Sie zum Senden des Aktivitätsprotokolls möchten.</span><span class="sxs-lookup"><span data-stu-id="1fac0-110">the resource id of the storage account to which you would like to send the Activity Log.</span></span></param>
        <param name="serviceBusRuleId"><span data-ttu-id="1fac0-111">Die Servicebus Regel-ID von der Servicebus-Namespace in dem Sie Event Hubs, die für das Aktivitätsprotokoll streaming erstellt haben möchten.</span><span class="sxs-lookup"><span data-stu-id="1fac0-111">The service bus rule ID of the service bus namespace in which you would like to have Event Hubs created for streaming the Activity Log.</span></span> <span data-ttu-id="1fac0-112">Die Regel-ID im Format ist: "{service Bus-Ressourcen-ID} /authorizationrules/ {Key-Name}".</span><span class="sxs-lookup"><span data-stu-id="1fac0-112">The rule ID is of the format: '{service bus resource ID}/authorizationrules/{key name}'.</span></span></param>
        <summary>
            <span data-ttu-id="1fac0-113">Initialisiert eine neue Instanz der LogProfileResourcePatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1fac0-113">Initializes a new instance of the LogProfileResourcePatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Categories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Categories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Categories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Categories" />
      <MemberSignature Language="VB.NET" Value="Public Property Categories As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Categories : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Categories" />
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
            <span data-ttu-id="1fac0-114">Ruft ab oder legt die Kategorien der Protokolle.</span><span class="sxs-lookup"><span data-stu-id="1fac0-114">Gets or sets the categories of the logs.</span></span> <span data-ttu-id="1fac0-115">Diese Kategorien werden als praktisch, den der Benutzer wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="1fac0-115">These categories are created as is convenient to the user.</span></span> <span data-ttu-id="1fac0-116">Einige Werte sind: "Schreiben", "Delete" und/oder "Action".</span><span class="sxs-lookup"><span data-stu-id="1fac0-116">Some values are: 'Write', 'Delete', and/or 'Action.'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Locations" />
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
            <span data-ttu-id="1fac0-117">Ruft ab oder legt die Liste der Regionen für die Aktivitätsprotokoll-Ereignisse gespeichert oder per Stream übertragen werden soll.</span><span class="sxs-lookup"><span data-stu-id="1fac0-117">Gets or sets list of regions for which Activity Log events should be stored or streamed.</span></span> <span data-ttu-id="1fac0-118">Es ist eine durch Trennzeichen getrennte Liste der gültigen ARM Speicherorte einschließlich "globalen" Speicherort.</span><span class="sxs-lookup"><span data-stu-id="1fac0-118">It is a comma separated list of valid ARM locations including the 'global' location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Monitor.Management.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.RetentionPolicy" />
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
            <span data-ttu-id="1fac0-119">Ruft ab oder legt die Aufbewahrungsrichtlinie für die Ereignisse im Protokoll.</span><span class="sxs-lookup"><span data-stu-id="1fac0-119">Gets or sets the retention policy for the events in the log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusRuleId">
      <MemberSignature Language="C#" Value="public string ServiceBusRuleId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.ServiceBusRuleId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusRuleId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusRuleId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.ServiceBusRuleId" />
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
            <span data-ttu-id="1fac0-120">Ermittelt oder definiert die Servicebus-Regel-ID von der Servicebus-Namespace in dem Sie Event Hubs, die für das Aktivitätsprotokoll streaming erstellt haben möchten.</span><span class="sxs-lookup"><span data-stu-id="1fac0-120">Gets or sets the service bus rule ID of the service bus namespace in which you would like to have Event Hubs created for streaming the Activity Log.</span></span> <span data-ttu-id="1fac0-121">Die Regel-ID im Format ist: "{service Bus-Ressourcen-ID} /authorizationrules/ {Key-Name}".</span><span class="sxs-lookup"><span data-stu-id="1fac0-121">The rule ID is of the format: '{service bus resource ID}/authorizationrules/{key name}'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.StorageAccountId" />
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
            <span data-ttu-id="1fac0-122">Ruft ab oder legt die Ressourcen-Id des Speicherkontos an, das Sie zum Senden des Aktivitätsprotokolls möchten.</span><span class="sxs-lookup"><span data-stu-id="1fac0-122">Gets or sets the resource id of the storage account to which you would like to send the Activity Log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="1fac0-123">Ruft ab oder legt ihn fest Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="1fac0-123">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="logProfileResourcePatch.Validate " />
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
            <span data-ttu-id="1fac0-124">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1fac0-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1fac0-125">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1fac0-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>