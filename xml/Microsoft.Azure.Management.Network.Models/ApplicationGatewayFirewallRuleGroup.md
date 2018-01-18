<Type Name="ApplicationGatewayFirewallRuleGroup" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayFirewallRuleGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayFirewallRuleGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayFirewallRuleGroup" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayFirewallRuleGroup = class" />
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
            <span data-ttu-id="6fcb7-101">Eine Web-Anwendung firewallregelgruppe.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-101">A web application firewall rule group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallRuleGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.#ctor" />
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
            <span data-ttu-id="6fcb7-102">Initialisiert eine neue Instanz der ApplicationGatewayFirewallRuleGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-102">Initializes a new instance of the ApplicationGatewayFirewallRuleGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallRuleGroup (string ruleGroupName, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt; rules, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ruleGroupName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt; rules, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ruleGroupName As String, rules As IList(Of ApplicationGatewayFirewallRule), Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup (ruleGroupName, rules, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ruleGroupName" Type="System.String" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt;" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleGroupName"><span data-ttu-id="6fcb7-103">Der Name des firewallregelgruppe der Web-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-103">The name of the web application firewall rule group.</span></span></param>
        <param name="rules"><span data-ttu-id="6fcb7-104">Die Regeln für die Web-Firewall-Regel Anwendungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-104">The rules of the web application firewall rule group.</span></span></param>
        <param name="description"><span data-ttu-id="6fcb7-105">Die Beschreibung des firewallregelgruppe der Web-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-105">The description of the web application firewall rule group.</span></span></param>
        <summary>
            <span data-ttu-id="6fcb7-106">Initialisiert eine neue Instanz der ApplicationGatewayFirewallRuleGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-106">Initializes a new instance of the ApplicationGatewayFirewallRuleGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fcb7-107">Ruft ab oder legt die Beschreibung für die Web-Firewall-Regel Anwendungsgruppe fest.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-107">Gets or sets the description of the web application firewall rule group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleGroupName">
      <MemberSignature Language="C#" Value="public string RuleGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.RuleGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleGroupName As String" />
      <MemberSignature Language="F#" Value="member this.RuleGroupName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.RuleGroupName" />
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
            <span data-ttu-id="6fcb7-108">Ruft ab oder legt den Namen der Regelgruppe an Web Application-Firewall fest.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-108">Gets or sets the name of the web application firewall rule group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of ApplicationGatewayFirewallRule)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.Rules" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fcb7-109">Ruft ab oder legt die Regeln für die Web-Firewall-Regel Anwendungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-109">Gets or sets the rules of the web application firewall rule group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayFirewallRuleGroup.Validate " />
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
            <span data-ttu-id="6fcb7-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6fcb7-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6fcb7-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6fcb7-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>