<Type Name="AlertRuleResourcePatch" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch">
  <TypeSignature Language="C#" Value="public class AlertRuleResourcePatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AlertRuleResourcePatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertRuleResourcePatch" />
  <TypeSignature Language="F#" Value="type AlertRuleResourcePatch = class" />
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
            <span data-ttu-id="669ad-101">Die Warnungsregel-Objekt für die Patch-Operationen.</span><span class="sxs-lookup"><span data-stu-id="669ad-101">The alert rule object for patch operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertRuleResourcePatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.#ctor" />
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
            <span data-ttu-id="669ad-102">Initialisiert eine neue Instanz der AlertRuleResourcePatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="669ad-102">Initializes a new instance of the AlertRuleResourcePatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertRuleResourcePatch (string name, bool isEnabled, Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition condition, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; actions = null, Nullable&lt;DateTime&gt; lastUpdatedTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, bool isEnabled, class Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition condition, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; actions, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.#ctor(System.String,System.Boolean,Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.RuleAction},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, isEnabled As Boolean, condition As RuleCondition, Optional tags As IDictionary(Of String, String) = null, Optional description As String = null, Optional actions As IList(Of RuleAction) = null, Optional lastUpdatedTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch : string * bool * Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch (name, isEnabled, condition, tags, description, actions, lastUpdatedTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="isEnabled" Type="System.Boolean" />
        <Parameter Name="condition" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt;" />
        <Parameter Name="lastUpdatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="669ad-103">der Name der Warnungsregel.</span><span class="sxs-lookup"><span data-stu-id="669ad-103">the name of the alert rule.</span></span></param>
        <param name="isEnabled"><span data-ttu-id="669ad-104">Das Flag, die angibt, ob die Warnregel aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="669ad-104">the flag that indicates whether the alert rule is enabled.</span></span></param>
        <param name="condition"><span data-ttu-id="669ad-105">die Bedingung, die in der Benachrichtigungsregel aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="669ad-105">the condition that results in the alert rule being activated.</span></span></param>
        <param name="tags"><span data-ttu-id="669ad-106">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="669ad-106">Resource tags</span></span></param>
        <param name="description"><span data-ttu-id="669ad-107">die Beschreibung der Warnregel, die in der warnungsbenachrichtigung per e-Mail eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="669ad-107">the description of the alert rule that will be included in the alert email.</span></span></param>
        <param name="actions"><span data-ttu-id="669ad-108">das Array von Aktionen, die ausgeführt werden, wenn die Warnregel aktiv ist, und nachdem eine warnungsbedingung aufgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="669ad-108">the array of actions that are performed when the alert rule becomes active, and when an alert condition is resolved.</span></span></param>
        <param name="lastUpdatedTime"><span data-ttu-id="669ad-109">Letzte Zeitpunkt, an die Regel im ISO8601-Format aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="669ad-109">Last time the rule was updated in ISO8601 format.</span></span></param>
        <summary>
            <span data-ttu-id="669ad-110">Initialisiert eine neue Instanz der AlertRuleResourcePatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="669ad-110">Initializes a new instance of the AlertRuleResourcePatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of RuleAction)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Actions" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="669ad-111">Ruft ab oder legt das Array von Aktionen, die ausgeführt werden, wenn die Warnregel aktiv ist, und wenn eine warnungsbedingung aufgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="669ad-111">Gets or sets the array of actions that are performed when the alert rule becomes active, and when an alert condition is resolved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As RuleCondition" />
      <MemberSignature Language="F#" Value="member this.Condition : Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Condition" />
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
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="669ad-112">Ruft ab oder legt die Bedingung, die in der Benachrichtigungsregel aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="669ad-112">Gets or sets the condition that results in the alert rule being activated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Description" />
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
            <span data-ttu-id="669ad-113">Ruft ab oder legt die Beschreibung der Warnregel, die in der warnungsbenachrichtigung per e-Mail eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="669ad-113">Gets or sets the description of the alert rule that will be included in the alert email.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.IsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="669ad-114">Ruft ab oder legt das Flag, die angibt, ob die Warnregel aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="669ad-114">Gets or sets the flag that indicates whether the alert rule is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.LastUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.LastUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastUpdatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="669ad-115">Ruft ab, wann zuletzt die Regel im ISO8601-Format aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="669ad-115">Gets last time the rule was updated in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="669ad-116">Ruft ab oder legt den Namen der Warnungsregel.</span><span class="sxs-lookup"><span data-stu-id="669ad-116">Gets or sets the name of the alert rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Tags" />
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
            <span data-ttu-id="669ad-117">Ruft ab oder legt ihn fest Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="669ad-117">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResourcePatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="alertRuleResourcePatch.Validate " />
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
            <span data-ttu-id="669ad-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="669ad-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="669ad-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="669ad-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>