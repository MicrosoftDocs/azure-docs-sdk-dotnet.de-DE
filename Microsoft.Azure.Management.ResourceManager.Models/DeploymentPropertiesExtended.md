<Type Name="DeploymentPropertiesExtended" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended">
  <TypeSignature Language="C#" Value="public class DeploymentPropertiesExtended" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentPropertiesExtended extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentPropertiesExtended" />
  <TypeSignature Language="F#" Value="type DeploymentPropertiesExtended = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bereitstellungseigenschaften mit zusätzlichen Details.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentPropertiesExtended ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DeploymentPropertiesExtended-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentPropertiesExtended (string provisioningState = null, string correlationId = null, Nullable&lt;DateTime&gt; timestamp = null, object outputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; providers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt; dependencies = null, object template = null, Microsoft.Azure.Management.ResourceManager.Models.TemplateLink templateLink = null, object parameters = null, Microsoft.Azure.Management.ResourceManager.Models.ParametersLink parametersLink = null, Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt; mode = null, Microsoft.Azure.Management.ResourceManager.Models.DebugSetting debugSetting = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provisioningState, string correlationId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, object outputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; providers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt; dependencies, object template, class Microsoft.Azure.Management.ResourceManager.Models.TemplateLink templateLink, object parameters, class Microsoft.Azure.Management.ResourceManager.Models.ParametersLink parametersLink, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt; mode, class Microsoft.Azure.Management.ResourceManager.Models.DebugSetting debugSetting) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Object,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.Provider},System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.Dependency},System.Object,Microsoft.Azure.Management.ResourceManager.Models.TemplateLink,System.Object,Microsoft.Azure.Management.ResourceManager.Models.ParametersLink,System.Nullable{Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode},Microsoft.Azure.Management.ResourceManager.Models.DebugSetting)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended : string * string * Nullable&lt;DateTime&gt; * obj * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt; * obj * Microsoft.Azure.Management.ResourceManager.Models.TemplateLink * obj * Microsoft.Azure.Management.ResourceManager.Models.ParametersLink * Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt; * Microsoft.Azure.Management.ResourceManager.Models.DebugSetting -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended (provisioningState, correlationId, timestamp, outputs, providers, dependencies, template, templateLink, parameters, parametersLink, mode, debugSetting)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="correlationId" Type="System.String" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="outputs" Type="System.Object" />
        <Parameter Name="providers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" />
        <Parameter Name="dependencies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt;" />
        <Parameter Name="template" Type="System.Object" />
        <Parameter Name="templateLink" Type="Microsoft.Azure.Management.ResourceManager.Models.TemplateLink" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="parametersLink" Type="Microsoft.Azure.Management.ResourceManager.Models.ParametersLink" />
        <Parameter Name="mode" Type="System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt;" />
        <Parameter Name="debugSetting" Type="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" />
      </Parameters>
      <Docs>
        <param name="provisioningState">Der Status der Bereitstellung.</param>
        <param name="correlationId">Die Korrelations-ID der Bereitstellung.</param>
        <param name="timestamp">Der Zeitstempel der vorlagenbereitstellung.</param>
        <param name="outputs">Schlüssel/Wert-Paaren, die Deploymentoutput darstellen.</param>
        <param name="providers">Die Liste der für die Bereitstellung erforderlichen Ressourcenanbieter.</param>
        <param name="dependencies">Die Liste der bereitstellungsabhängigkeiten.</param>
        <param name="template">Der Inhalt der Vorlage. Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.</param>
        <param name="templateLink">Der URI, der auf die Vorlage verweist. Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.</param>
        <param name="parameters">Deployment-Parameter. Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.</param>
        <param name="parametersLink">Der URI, verweisen auf die Parameter.
            Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.</param>
        <param name="mode">Der Bereitstellungsmodus. Mögliche Werte sind inkrementelle und vollständige. Folgende Werte sind möglich: "Inkrementell", "Abgeschlossen"</param>
        <param name="debugSetting">Die Debugeinstellung der Bereitstellung.</param>
        <summary>
            Initialisiert eine neue Instanz der DeploymentPropertiesExtended-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Korrelations-ID der Bereitstellung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DebugSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DebugSetting DebugSetting { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.DebugSetting DebugSetting" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.DebugSetting" />
      <MemberSignature Language="VB.NET" Value="Public Property DebugSetting As DebugSetting" />
      <MemberSignature Language="F#" Value="member this.DebugSetting : Microsoft.Azure.Management.ResourceManager.Models.DebugSetting with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.DebugSetting" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="debugSetting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DebugSetting</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Debug-Einstellung der Bereitstellung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dependencies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt; Dependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt; Dependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Dependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property Dependencies As IList(Of Dependency)" />
      <MemberSignature Language="F#" Value="member this.Dependencies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Dependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Dependency&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der bereitstellungsabhängigkeiten fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt; Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt; Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As Nullable(Of DeploymentMode)" />
      <MemberSignature Language="F#" Value="member this.Mode : Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Bereitstellungsmodus. Mögliche Werte sind inkrementelle und vollständige. Folgende Werte sind möglich: "Inkrementell", "Abgeschlossen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public object Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As Object" />
      <MemberSignature Language="F#" Value="member this.Outputs : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Schlüssel/Wert-Paaren, die Deploymentoutput darstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Bereitstellungsparameter. Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ParametersLink ParametersLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ParametersLink ParametersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.ParametersLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ParametersLink As ParametersLink" />
      <MemberSignature Language="F#" Value="member this.ParametersLink : Microsoft.Azure.Management.ResourceManager.Models.ParametersLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.ParametersLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parametersLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ParametersLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den URI verweisen auf die Parameter fest. Verwenden Sie nur eine Kopie der Parameter oder den ParametersLink.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Providers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; Providers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; Providers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Providers" />
      <MemberSignature Language="VB.NET" Value="Public Property Providers As IList(Of Provider)" />
      <MemberSignature Language="F#" Value="member this.Providers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Providers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der für die Bereitstellung erforderlichen Ressourcenanbieter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status der Bereitstellung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public object Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As Object" />
      <MemberSignature Language="F#" Value="member this.Template : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Template" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="template")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Vorlageninhalt. Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TemplateLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.TemplateLink TemplateLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.TemplateLink TemplateLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.TemplateLink" />
      <MemberSignature Language="VB.NET" Value="Public Property TemplateLink As TemplateLink" />
      <MemberSignature Language="F#" Value="member this.TemplateLink : Microsoft.Azure.Management.ResourceManager.Models.TemplateLink with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.TemplateLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="templateLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TemplateLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den URI, der auf die Vorlage verweist. Verwenden Sie nur eine Kopie der Vorlagen oder den TemplateLink.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitstempel der vorlagenbereitstellung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentPropertiesExtended.Validate " />
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