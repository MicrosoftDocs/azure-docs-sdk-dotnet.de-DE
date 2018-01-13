<Type Name="AlertRuleResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource">
  <TypeSignature Language="C#" Value="public class AlertRuleResource : Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AlertRuleResource extends Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertRuleResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AlertRuleResource = class&#xA;    inherit Resource" />
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
            Die Warnregel-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertRuleResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.#ctor" />
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
            Initialisiert eine neue Instanz der AlertRuleResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertRuleResource (string location, string alertRuleResourceName, bool isEnabled, Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition condition, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; actions = null, Nullable&lt;DateTime&gt; lastUpdatedTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string alertRuleResourceName, bool isEnabled, class Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition condition, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; actions, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.#ctor(System.String,System.String,System.Boolean,Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.RuleAction},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, alertRuleResourceName As String, isEnabled As Boolean, condition As RuleCondition, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional description As String = null, Optional actions As IList(Of RuleAction) = null, Optional lastUpdatedTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource : string * string * bool * Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource (location, alertRuleResourceName, isEnabled, condition, id, name, type, tags, description, actions, lastUpdatedTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="alertRuleResourceName" Type="System.String" />
        <Parameter Name="isEnabled" Type="System.Boolean" />
        <Parameter Name="condition" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt;" />
        <Parameter Name="lastUpdatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="alertRuleResourceName">der Name der Warnungsregel.</param>
        <param name="isEnabled">Das Flag, die angibt, ob die Warnregel aktiviert ist.</param>
        <param name="condition">die Bedingung, die in der Benachrichtigungsregel aktiviert wird.</param>
        <param name="id">Azure-Ressourcen-Id</param>
        <param name="name">Name des Azure-Ressource</param>
        <param name="type">Azure-Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="description">die Beschreibung der Warnregel, die in der warnungsbenachrichtigung per e-Mail eingeschlossen werden sollen.</param>
        <param name="actions">das Array von Aktionen, die ausgeführt werden, wenn die Warnregel aktiv ist, und nachdem eine warnungsbedingung aufgelöst wurde.</param>
        <param name="lastUpdatedTime">Letzte Zeitpunkt, an die Regel im ISO8601-Format aktualisiert wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der AlertRuleResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of RuleAction)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.RuleAction&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Actions" />
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
            Ruft ab oder legt das Array von Aktionen, die ausgeführt werden, wenn die Warnregel aktiv ist, und wenn eine warnungsbedingung aufgelöst wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertRuleResourceName">
      <MemberSignature Language="C#" Value="public string AlertRuleResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlertRuleResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.AlertRuleResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AlertRuleResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AlertRuleResourceName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.AlertRuleResourceName" />
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
            Ruft ab oder legt den Namen der Warnungsregel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As RuleCondition" />
      <MemberSignature Language="F#" Value="member this.Condition : Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Condition" />
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
            Ruft ab oder legt die Bedingung, die in der Benachrichtigungsregel aktiviert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Description" />
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
            Ruft ab oder legt die Beschreibung der Warnregel, die in der warnungsbenachrichtigung per e-Mail eingeschlossen werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.IsEnabled" />
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
            Ruft ab oder legt das Flag, die angibt, ob die Warnregel aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.LastUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.LastUpdatedTime" />
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
            Ruft ab, wann zuletzt die Regel im ISO8601-Format aktualisiert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AlertRuleResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="alertRuleResource.Validate " />
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>