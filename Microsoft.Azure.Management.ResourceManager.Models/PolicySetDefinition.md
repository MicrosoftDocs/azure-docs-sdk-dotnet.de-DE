<Type Name="PolicySetDefinition" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition">
  <TypeSignature Language="C#" Value="public class PolicySetDefinition : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicySetDefinition extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicySetDefinition&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type PolicySetDefinition = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Richtlinie festgelegt Definition.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicySetDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PolicySetDefinition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicySetDefinition (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; policyDefinitions, string policyType = null, string displayName = null, string description = null, object metadata = null, object parameters = null, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; policyDefinitions, string policyType, string displayName, string description, object metadata, object parameters, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference},System.String,System.String,System.String,System.Object,System.Object,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (policyDefinitions As IList(Of PolicyDefinitionReference), Optional policyType As String = null, Optional displayName As String = null, Optional description As String = null, Optional metadata As Object = null, Optional parameters As Object = null, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; * string * string * string * obj * obj * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition (policyDefinitions, policyType, displayName, description, metadata, parameters, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyDefinitions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt;" />
        <Parameter Name="policyType" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="metadata" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyDefinitions">Ein Array von Definition verweisen.</param>
        <param name="policyType">Der Typ der Richtliniendefinition. Mögliche Werte sind "NotSpecified", "Vordefiniert" und benutzerdefinierte. Folgende Werte sind möglich: "NotSpecified" "", "Vordefiniert" "", "Custom"</param>
        <param name="displayName">Der Anzeigename der Richtlinie festgelegt Definition.</param>
        <param name="description">Die Richtlinie festgelegt definitionsbeschreibung.</param>
        <param name="metadata">Die Richtlinie festgelegt, die Metadaten-Definition.</param>
        <param name="parameters">Die Richtlinie festgelegt Definition-Parameter, die verwendet werden können, in der Definition verweisen.</param>
        <param name="id">Die ID der Richtlinie festgelegt Definition.</param>
        <param name="name">Der Name der Richtlinie festgelegt Definition.</param>
        <param name="type">Der Typ der Ressource (Microsoft.Authorization/policySetDefinitions).</param>
        <summary>
            Initialisiert eine neue Instanz der PolicySetDefinition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Abrufen oder Festlegen der Richtlinie Satz definitionsbeschreibung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest der Anzeigenamen der Richtlinie Definition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID der Definition der Richtlinie ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public object Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As Object" />
      <MemberSignature Language="F#" Value="member this.Metadata : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Metadaten der Richtlinie Set-Definition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Namen der Richtlinie festgelegten Definition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Im abruft oder festlegt Satz Definition Richtlinienparameter, die verwendet werden können Definition verweisen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyDefinitions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; PolicyDefinitions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; PolicyDefinitions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyDefinitions" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyDefinitions As IList(Of PolicyDefinitionReference)" />
      <MemberSignature Language="F#" Value="member this.PolicyDefinitions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyDefinitions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyDefinitions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Array von Definition verweisen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyType">
      <MemberSignature Language="C#" Value="public string PolicyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyType" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyType As String" />
      <MemberSignature Language="F#" Value="member this.PolicyType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.PolicyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Richtliniendefinition fest. Mögliche Werte sind "NotSpecified", "Vordefiniert" und benutzerdefinierte. Folgende Werte sind möglich: "NotSpecified" "", "Vordefiniert" "", "Custom"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ der Ressource (Microsoft.Authorization/policySetDefinitions) ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="policySetDefinition.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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