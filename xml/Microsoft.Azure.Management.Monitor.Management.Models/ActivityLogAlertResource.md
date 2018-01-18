<Type Name="ActivityLogAlertResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertResource : Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertResource extends Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="35add-101">Eine Aktivität Ressource "Log Warnung".</span><span class="sxs-lookup"><span data-stu-id="35add-101">An activity log alert resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.#ctor" />
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
            <span data-ttu-id="35add-102">Initialisiert eine neue Instanz der ActivityLogAlertResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35add-102">Initializes a new instance of the ActivityLogAlertResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertResource (string location, System.Collections.Generic.IList&lt;string&gt; scopes, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition condition, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList actions, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; enabled = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;string&gt; scopes, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition condition, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList actions, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; enabled, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.#ctor(System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition,Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, scopes As IList(Of String), condition As ActivityLogAlertAllOfCondition, actions As ActivityLogAlertActionList, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional enabled As Nullable(Of Boolean) = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource : string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource (location, scopes, condition, actions, id, name, type, tags, enabled, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="condition" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition" />
        <Parameter Name="actions" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="35add-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="35add-103">Resource location</span></span></param>
        <param name="scopes"><span data-ttu-id="35add-104">Eine Liste der Ressourcen-IDs, die als Präfix verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="35add-104">A list of resourceIds that will be used as prefixes.</span></span> <span data-ttu-id="35add-105">Die Warnung gelten nur für ActivityLogs mit Ressourcen-IDs, die unter einem dieser Präfixe liegen.</span><span class="sxs-lookup"><span data-stu-id="35add-105">The alert will only apply to activityLogs with resourceIds that fall under one of these prefixes.</span></span> <span data-ttu-id="35add-106">Diese Liste muss mindestens ein Element enthalten.</span><span class="sxs-lookup"><span data-stu-id="35add-106">This list must include at least one item.</span></span></param>
        <param name="condition"><span data-ttu-id="35add-107">Die Bedingung, die bewirkt diese Warnung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="35add-107">The condition that will cause this alert to activate.</span></span></param>
        <param name="actions"><span data-ttu-id="35add-108">Die Aktionen, die aktiviert werden, wenn die Bedingung erfüllt ist.</span><span class="sxs-lookup"><span data-stu-id="35add-108">The actions that will activate when the condition is met.</span></span></param>
        <param name="id"><span data-ttu-id="35add-109">Azure-Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="35add-109">Azure resource Id</span></span></param>
        <param name="name"><span data-ttu-id="35add-110">Name des Azure-Ressource</span><span class="sxs-lookup"><span data-stu-id="35add-110">Azure resource name</span></span></param>
        <param name="type"><span data-ttu-id="35add-111">Azure-Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="35add-111">Azure resource type</span></span></param>
        <param name="tags"><span data-ttu-id="35add-112">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="35add-112">Resource tags</span></span></param>
        <param name="enabled"><span data-ttu-id="35add-113">Gibt an, ob diese Warnung zu Clientaktivität Protokoll aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="35add-113">Indicates whether this activity log alert is enabled.</span></span> <span data-ttu-id="35add-114">Wenn eine Warnung zu Clientaktivität Protokoll nicht aktiviert ist, wird keine der zugehörigen Aktionen aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="35add-114">If an activity log alert is not enabled, then none of its actions will be activated.</span></span></param>
        <param name="description"><span data-ttu-id="35add-115">Eine Beschreibung dieser Aktivität Protokoll-Warnung.</span><span class="sxs-lookup"><span data-stu-id="35add-115">A description of this activity log alert.</span></span></param>
        <summary>
            <span data-ttu-id="35add-116">Initialisiert eine neue Instanz der ActivityLogAlertResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35add-116">Initializes a new instance of the ActivityLogAlertResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As ActivityLogAlertActionList" />
      <MemberSignature Language="F#" Value="member this.Actions : Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.actions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35add-117">Ruft ab oder legt die Aktionen, die aktiviert werden, wenn die Bedingung erfüllt ist.</span><span class="sxs-lookup"><span data-stu-id="35add-117">Gets or sets the actions that will activate when the condition is met.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As ActivityLogAlertAllOfCondition" />
      <MemberSignature Language="F#" Value="member this.Condition : Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Condition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.condition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35add-118">Ruft ab oder legt die Bedingung, die bewirkt diese Warnung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="35add-118">Gets or sets the condition that will cause this alert to activate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35add-119">Ermittelt oder definiert eine Beschreibung dieser Aktivität Protokoll-Warnung.</span><span class="sxs-lookup"><span data-stu-id="35add-119">Gets or sets a description of this activity log alert.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35add-120">Gibt an, ob diese Warnung zu Clientaktivität Protokoll aktiviert ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="35add-120">Gets or sets indicates whether this activity log alert is enabled.</span></span>
            <span data-ttu-id="35add-121">Wenn eine Warnung zu Clientaktivität Protokoll nicht aktiviert ist, wird keine der zugehörigen Aktionen aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="35add-121">If an activity log alert is not enabled, then none of its actions will be activated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Scopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Scopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Scopes" />
      <MemberSignature Language="VB.NET" Value="Public Property Scopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Scopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Scopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35add-122">Ruft ab oder legt eine Liste der Ressourcen-IDs, die als Präfix verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="35add-122">Gets or sets a list of resourceIds that will be used as prefixes.</span></span>
            <span data-ttu-id="35add-123">Die Warnung gelten nur für ActivityLogs mit Ressourcen-IDs, die unter einem dieser Präfixe liegen.</span><span class="sxs-lookup"><span data-stu-id="35add-123">The alert will only apply to activityLogs with resourceIds that fall under one of these prefixes.</span></span> <span data-ttu-id="35add-124">Diese Liste muss mindestens ein Element enthalten.</span><span class="sxs-lookup"><span data-stu-id="35add-124">This list must include at least one item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="activityLogAlertResource.Validate " />
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
            <span data-ttu-id="35add-125">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="35add-125">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35add-126">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="35add-126">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>