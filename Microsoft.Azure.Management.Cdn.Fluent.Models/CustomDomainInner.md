<Type Name="CustomDomainInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner">
  <TypeSignature Language="C#" Value="public class CustomDomainInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomDomainInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomDomainInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type CustomDomainInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Domäne wird von Kunden für die Zwecke, z. B. www.consoto.com branding bereitgestellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomainInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CustomDomainInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomainInner (string hostName, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string resourceState = null, string customHttpsProvisioningState = null, string validationData = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string resourceState, string customHttpsProvisioningState, string validationData, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional resourceState As String = null, Optional customHttpsProvisioningState As String = null, Optional validationData As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner (hostName, location, id, name, type, tags, resourceState, customHttpsProvisioningState, validationData, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="resourceState" Type="System.String" />
        <Parameter Name="customHttpsProvisioningState" Type="System.String" />
        <Parameter Name="validationData" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">Der Hostname der benutzerdefinierten Domäne. Ein Domänenname muss sein.</param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="resourceState">Ressourcenstatus der benutzerdefinierten Domäne.
            Folgende Werte sind möglich: 'Erstellen', 'Active', 'Löschen'</param>
        <param name="customHttpsProvisioningState">Der Bereitstellungsstatus der benutzerdefinierten Https der benutzerdefinierten Domäne. Folgende Werte sind möglich: "Aktivieren", "Enabled", "Deaktivieren", "Disabled", "Fehlgeschlagen"</param>
        <param name="validationData">Spezielle Validierungs- oder Daten können erforderlich sein, wenn in einigen Regionen lokale Compliance-Gründen CDN übermittelt. Beispiel: ICP-Lizenznummer einer benutzerdefinierten Domäne ist erforderlich, um die Bereitstellung von Inhalten in China.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der benutzerdefinierten Domäne.</param>
        <summary>
            Initialisiert eine neue Instanz der CustomDomainInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHttpsProvisioningState">
      <MemberSignature Language="C#" Value="public string CustomHttpsProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomHttpsProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.CustomHttpsProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomHttpsProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.CustomHttpsProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.CustomHttpsProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customHttpsProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Status von benutzerdefinierten Https der benutzerdefinierten Domäne ruft bereitgestellt werden.
            Folgende Werte sind möglich: "Aktivieren", "Enabled", "Deaktivieren", "Disabled", "Fehlgeschlagen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hostnamen der benutzerdefinierten Domäne fest. Ein Domänenname muss sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Status der benutzerdefinierten Domäne bereitstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die benutzerdefinierte Domäne Ressourcenstatus ab. Folgende Werte sind möglich: 'Erstellen', 'Active', 'Löschen'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customDomainInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="ValidationData">
      <MemberSignature Language="C#" Value="public string ValidationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValidationData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ValidationData" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidationData As String" />
      <MemberSignature Language="F#" Value="member this.ValidationData : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner.ValidationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.validationData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt spezielle Validierungs- oder Daten können erforderlich sein, wenn in einigen Regionen lokale Compliance-Gründen CDN übermittelt.
            Beispiel: ICP-Lizenznummer einer benutzerdefinierten Domäne ist erforderlich, um die Bereitstellung von Inhalten in China.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>