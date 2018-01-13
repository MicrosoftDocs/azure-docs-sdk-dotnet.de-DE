<Type Name="AutoscaleSettingResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource">
  <TypeSignature Language="C#" Value="public class AutoscaleSettingResource : Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoscaleSettingResource extends Microsoft.Azure.Management.Monitor.Management.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoscaleSettingResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AutoscaleSettingResource = class&#xA;    inherit Resource" />
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
            Die automatische Skalierung Einstellung-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleSettingResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.#ctor" />
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
            Initialisiert eine neue Instanz der AutoscaleSettingResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleSettingResource (string location, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; profiles, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; notifications = null, Nullable&lt;bool&gt; enabled = null, string autoscaleSettingResourceName = null, string targetResourceUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; profiles, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; notifications, valuetype System.Nullable`1&lt;bool&gt; enabled, string autoscaleSettingResourceName, string targetResourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, profiles As IList(Of AutoscaleProfile), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional notifications As IList(Of AutoscaleNotification) = null, Optional enabled As Nullable(Of Boolean) = null, Optional autoscaleSettingResourceName As String = null, Optional targetResourceUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource (location, profiles, id, name, type, tags, notifications, enabled, autoscaleSettingResourceName, targetResourceUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="profiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="notifications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoscaleSettingResourceName" Type="System.String" />
        <Parameter Name="targetResourceUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="profiles">die Auflistung der automatischen skalierungsprofile, die verschiedene Skalierungsparameter für unterschiedliche Zeiträume angeben. Es kann maximal 20 Profile angegeben werden.</param>
        <param name="id">Azure-Ressourcen-Id</param>
        <param name="name">Name des Azure-Ressource</param>
        <param name="type">Azure-Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="notifications">die Auflistung von Benachrichtigungen.</param>
        <param name="enabled">das Kennzeichen "enabled". Gibt an, ob die automatische Skalierung für die Ressource aktiviert ist. Der Standardwert ist 'true'.</param>
        <param name="autoscaleSettingResourceName">der Name der automatischen skalierungseinstellung.</param>
        <param name="targetResourceUri">Der Ressourcenbezeichner der Ressource, der die skalierungseinstellung zur automatischen hinzugefügt werden sollen.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoscaleSettingResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoscaleSettingResourceName">
      <MemberSignature Language="C#" Value="public string AutoscaleSettingResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoscaleSettingResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.AutoscaleSettingResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoscaleSettingResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AutoscaleSettingResourceName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.AutoscaleSettingResourceName" />
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
            Ruft ab oder legt den Namen für die automatische Skalierung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Enabled" />
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
            Ruft ab oder legt das Kennzeichen "enabled". Gibt an, ob die automatische Skalierung für die Ressource aktiviert ist. Der Standardwert ist 'true'.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notifications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; Notifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; Notifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Notifications" />
      <MemberSignature Language="VB.NET" Value="Public Property Notifications As IList(Of AutoscaleNotification)" />
      <MemberSignature Language="F#" Value="member this.Notifications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Notifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.notifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung von Benachrichtigungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Profiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; Profiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; Profiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Profiles" />
      <MemberSignature Language="VB.NET" Value="Public Property Profiles As IList(Of AutoscaleProfile)" />
      <MemberSignature Language="F#" Value="member this.Profiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Profiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.profiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung der automatischen skalierungsprofile, die verschiedene Skalierungsparameter für unterschiedliche Zeiträume angeben. Es kann maximal 20 Profile angegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceUri">
      <MemberSignature Language="C#" Value="public string TargetResourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.TargetResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.TargetResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetResourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Ressourcenbezeichner der Ressource, der die skalierungseinstellung zur automatischen hinzugefügt werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleSettingResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="autoscaleSettingResource.Validate " />
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