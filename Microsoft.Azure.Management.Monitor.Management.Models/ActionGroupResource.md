<Type Name="ActionGroupResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource">
  <TypeSignature Language="C#" Value="public class ActionGroupResource : Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActionGroupResource extends Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" />
  <TypeSignature Language="VB.NET" Value="Public Class ActionGroupResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ActionGroupResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="63999-101">Eine Aktion Group-Ressource.</span><span class="sxs-lookup"><span data-stu-id="63999-101">An action group resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActionGroupResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.#ctor" />
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
            <span data-ttu-id="63999-102">Initialisiert eine neue Instanz der ActionGroupResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63999-102">Initializes a new instance of the ActionGroupResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActionGroupResource (string location, string groupShortName, bool enabled, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt; emailReceivers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt; smsReceivers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt; webhookReceivers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string groupShortName, bool enabled, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt; emailReceivers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt; smsReceivers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt; webhookReceivers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.#ctor(System.String,System.String,System.Boolean,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, groupShortName As String, enabled As Boolean, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional emailReceivers As IList(Of EmailReceiver) = null, Optional smsReceivers As IList(Of SmsReceiver) = null, Optional webhookReceivers As IList(Of WebhookReceiver) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource : string * string * bool * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource (location, groupShortName, enabled, id, name, type, tags, emailReceivers, smsReceivers, webhookReceivers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="groupShortName" Type="System.String" />
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="emailReceivers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt;" />
        <Parameter Name="smsReceivers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt;" />
        <Parameter Name="webhookReceivers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="63999-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="63999-103">Resource location</span></span></param>
        <param name="groupShortName"><span data-ttu-id="63999-104">Der kurze Name der Gruppe "Aktion".</span><span class="sxs-lookup"><span data-stu-id="63999-104">The short name of the action group.</span></span>
            <span data-ttu-id="63999-105">Dies wird in der SMS-Nachrichten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="63999-105">This will be used in SMS messages.</span></span></param>
        <param name="enabled"><span data-ttu-id="63999-106">Gibt an, ob diese Aktionsgruppe aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="63999-106">Indicates whether this action group is enabled.</span></span> <span data-ttu-id="63999-107">Wenn Sie eine Aktivitätsgruppe nicht aktiviert ist, wird keines der Empfänger Kommunikation empfangen.</span><span class="sxs-lookup"><span data-stu-id="63999-107">If an action group is not enabled, then none of its receivers will receive communications.</span></span></param>
        <param name="id"><span data-ttu-id="63999-108">Azure-Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="63999-108">Azure resource Id</span></span></param>
        <param name="name"><span data-ttu-id="63999-109">Name des Azure-Ressource</span><span class="sxs-lookup"><span data-stu-id="63999-109">Azure resource name</span></span></param>
        <param name="type"><span data-ttu-id="63999-110">Azure-Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="63999-110">Azure resource type</span></span></param>
        <param name="tags"><span data-ttu-id="63999-111">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="63999-111">Resource tags</span></span></param>
        <param name="emailReceivers"><span data-ttu-id="63999-112">Die Liste der e-Mail-Empfänger, die Teil dieser Aktion Gruppe sind.</span><span class="sxs-lookup"><span data-stu-id="63999-112">The list of email receivers that are part of this action group.</span></span></param>
        <param name="smsReceivers"><span data-ttu-id="63999-113">Die Liste der SMS-Empfängern, die Teil dieser Aktion Gruppe sind.</span><span class="sxs-lookup"><span data-stu-id="63999-113">The list of SMS receivers that are part of this action group.</span></span></param>
        <param name="webhookReceivers"><span data-ttu-id="63999-114">Die Liste der Webhook Empfänger, die Teil dieser Aktion Gruppe sind.</span><span class="sxs-lookup"><span data-stu-id="63999-114">The list of webhook receivers that are part of this action group.</span></span></param>
        <summary>
            <span data-ttu-id="63999-115">Initialisiert eine neue Instanz der ActionGroupResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63999-115">Initializes a new instance of the ActionGroupResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailReceivers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt; EmailReceivers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt; EmailReceivers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.EmailReceivers" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailReceivers As IList(Of EmailReceiver)" />
      <MemberSignature Language="F#" Value="member this.EmailReceivers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.EmailReceivers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailReceivers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63999-116">Ruft ab oder legt die Liste der e-Mail-Empfänger, die Teil dieser Aktion Gruppe sind.</span><span class="sxs-lookup"><span data-stu-id="63999-116">Gets or sets the list of email receivers that are part of this action group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.Enabled" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63999-117">Gibt an, ob es sich bei dieser Aktionsgruppe aktiviert ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="63999-117">Gets or sets indicates whether this action group is enabled.</span></span> <span data-ttu-id="63999-118">Wenn Sie eine Aktivitätsgruppe nicht aktiviert ist, wird keines der Empfänger Kommunikation empfangen.</span><span class="sxs-lookup"><span data-stu-id="63999-118">If an action group is not enabled, then none of its receivers will receive communications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupShortName">
      <MemberSignature Language="C#" Value="public string GroupShortName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupShortName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.GroupShortName" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupShortName As String" />
      <MemberSignature Language="F#" Value="member this.GroupShortName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.GroupShortName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.groupShortName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63999-119">Ruft ab oder legt den Kurznamen der Gruppe "Aktion".</span><span class="sxs-lookup"><span data-stu-id="63999-119">Gets or sets the short name of the action group.</span></span> <span data-ttu-id="63999-120">Dies wird in der SMS-Nachrichten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="63999-120">This will be used in SMS messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SmsReceivers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt; SmsReceivers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt; SmsReceivers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.SmsReceivers" />
      <MemberSignature Language="VB.NET" Value="Public Property SmsReceivers As IList(Of SmsReceiver)" />
      <MemberSignature Language="F#" Value="member this.SmsReceivers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.SmsReceivers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.smsReceivers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63999-121">Ruft ab oder legt die Liste der SMS-Empfängern, die Teil dieser Aktion Gruppe sind.</span><span class="sxs-lookup"><span data-stu-id="63999-121">Gets or sets the list of SMS receivers that are part of this action group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="actionGroupResource.Validate " />
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
            <span data-ttu-id="63999-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="63999-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63999-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="63999-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WebhookReceivers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt; WebhookReceivers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt; WebhookReceivers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.WebhookReceivers" />
      <MemberSignature Language="VB.NET" Value="Public Property WebhookReceivers As IList(Of WebhookReceiver)" />
      <MemberSignature Language="F#" Value="member this.WebhookReceivers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource.WebhookReceivers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webhookReceivers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63999-124">Ruft ab oder legt die Liste der Webhook Empfänger, die Teil dieser Aktion Gruppe sind.</span><span class="sxs-lookup"><span data-stu-id="63999-124">Gets or sets the list of webhook receivers that are part of this action group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>