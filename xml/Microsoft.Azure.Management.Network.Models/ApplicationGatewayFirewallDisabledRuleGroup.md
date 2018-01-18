<Type Name="ApplicationGatewayFirewallDisabledRuleGroup" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayFirewallDisabledRuleGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayFirewallDisabledRuleGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayFirewallDisabledRuleGroup" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayFirewallDisabledRuleGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="07380-101">Ermöglicht das Deaktivieren von Regeln in einer Regelgruppe enthalten ist oder eine gesamte Regelgruppe enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="07380-101">Allows to disable rules within a rule group or an entire rule group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallDisabledRuleGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07380-102">Initialisiert eine neue Instanz der ApplicationGatewayFirewallDisabledRuleGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07380-102">Initializes a new instance of the ApplicationGatewayFirewallDisabledRuleGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallDisabledRuleGroup (string ruleGroupName, System.Collections.Generic.IList&lt;int&gt; rules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ruleGroupName, class System.Collections.Generic.IList`1&lt;int32&gt; rules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.#ctor(System.String,System.Collections.Generic.IList{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ruleGroupName As String, Optional rules As IList(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup : string * System.Collections.Generic.IList&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup (ruleGroupName, rules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ruleGroupName" Type="System.String" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="ruleGroupName"><span data-ttu-id="07380-103">Der Name der Gruppe "Regel", die deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="07380-103">The name of the rule group that will be disabled.</span></span></param>
        <param name="rules"><span data-ttu-id="07380-104">Die Liste der Regeln, die deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="07380-104">The list of rules that will be disabled.</span></span> <span data-ttu-id="07380-105">Wenn der Wert null ist, werden alle Regeln der Gruppe "Regel" deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="07380-105">If null, all rules of the rule group will be disabled.</span></span></param>
        <summary>
            <span data-ttu-id="07380-106">Initialisiert eine neue Instanz der ApplicationGatewayFirewallDisabledRuleGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07380-106">Initializes a new instance of the ApplicationGatewayFirewallDisabledRuleGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleGroupName">
      <MemberSignature Language="C#" Value="public string RuleGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.RuleGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleGroupName As String" />
      <MemberSignature Language="F#" Value="member this.RuleGroupName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.RuleGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07380-107">Ruft ab oder legt den Namen der Gruppe "Regel", die deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="07380-107">Gets or sets the name of the rule group that will be disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;int&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;int32&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07380-108">Ruft ab oder legt die Liste der Regeln, die deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="07380-108">Gets or sets the list of rules that will be disabled.</span></span> <span data-ttu-id="07380-109">Wenn der Wert null ist, werden alle Regeln der Gruppe "Regel" deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="07380-109">If null, all rules of the rule group will be disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayFirewallDisabledRuleGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07380-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="07380-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07380-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="07380-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>