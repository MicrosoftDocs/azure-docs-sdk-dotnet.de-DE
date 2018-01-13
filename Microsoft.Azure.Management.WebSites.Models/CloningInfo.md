<Type Name="CloningInfo" FullName="Microsoft.Azure.Management.WebSites.Models.CloningInfo">
  <TypeSignature Language="C#" Value="public class CloningInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloningInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CloningInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class CloningInfo" />
  <TypeSignature Language="F#" Value="type CloningInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Für das Klonen Vorgang erforderlichen Informationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloningInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CloningInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CloningInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloningInfo (string sourceWebAppId, Nullable&lt;Guid&gt; correlationId = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;bool&gt; cloneCustomHostNames = null, Nullable&lt;bool&gt; cloneSourceControl = null, string hostingEnvironment = null, System.Collections.Generic.IDictionary&lt;string,string&gt; appSettingsOverrides = null, Nullable&lt;bool&gt; configureLoadBalancing = null, string trafficManagerProfileId = null, string trafficManagerProfileName = null, Nullable&lt;bool&gt; ignoreQuotas = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceWebAppId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; correlationId, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;bool&gt; cloneCustomHostNames, valuetype System.Nullable`1&lt;bool&gt; cloneSourceControl, string hostingEnvironment, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; appSettingsOverrides, valuetype System.Nullable`1&lt;bool&gt; configureLoadBalancing, string trafficManagerProfileId, string trafficManagerProfileName, valuetype System.Nullable`1&lt;bool&gt; ignoreQuotas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CloningInfo.#ctor(System.String,System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceWebAppId As String, Optional correlationId As Nullable(Of Guid) = null, Optional overwrite As Nullable(Of Boolean) = null, Optional cloneCustomHostNames As Nullable(Of Boolean) = null, Optional cloneSourceControl As Nullable(Of Boolean) = null, Optional hostingEnvironment As String = null, Optional appSettingsOverrides As IDictionary(Of String, String) = null, Optional configureLoadBalancing As Nullable(Of Boolean) = null, Optional trafficManagerProfileId As String = null, Optional trafficManagerProfileName As String = null, Optional ignoreQuotas As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CloningInfo : string * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CloningInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.CloningInfo (sourceWebAppId, correlationId, overwrite, cloneCustomHostNames, cloneSourceControl, hostingEnvironment, appSettingsOverrides, configureLoadBalancing, trafficManagerProfileId, trafficManagerProfileName, ignoreQuotas)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceWebAppId" Type="System.String" />
        <Parameter Name="correlationId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cloneCustomHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cloneSourceControl" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
        <Parameter Name="appSettingsOverrides" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="configureLoadBalancing" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="trafficManagerProfileId" Type="System.String" />
        <Parameter Name="trafficManagerProfileName" Type="System.String" />
        <Parameter Name="ignoreQuotas" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sourceWebAppId">ARM-Ressourcen-ID der Quelle-app. App-Ressourcen-ID, der die Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName ist} für produktionsslots und /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} für andere Steckplätze.</param>
        <param name="correlationId">Korrelations-ID des klonprozesses.
            Diese ID verknüpft mehrere Klonvorgängen zusammen, um die gleichen Momentaufnahme zu verwenden.</param>
        <param name="overwrite">&lt;Code&gt;"true"&lt;/code&gt; zum Überschreiben der Ziel-app; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="cloneCustomHostNames">&lt;Code&gt;"true"&lt;/code&gt; benutzerdefinierte Hostnamen aus Quelle-app zu klonen, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="cloneSourceControl">&lt;Code&gt;"true"&lt;/code&gt; Datenquellen-Steuerelement aus der Quelle-app zu klonen, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="hostingEnvironment">App Service-Umgebung.</param>
        <param name="appSettingsOverrides">Anwendung Festlegen von Außerkraftsetzungen für die geklonte app. Diese Einstellungen überschreiben, wenn angegeben, die Einstellungen aus der Quelle-app geklont. Andernfalls werden die Anwendungseinstellungen von Quell-app beibehalten.</param>
        <param name="configureLoadBalancing">&lt;Code&gt;"true"&lt;/code&gt; so konfigurieren Sie einen Lastenausgleich für die Quelle und Ziel-app.</param>
        <param name="trafficManagerProfileId">ARM Ressourcen-ID der Traffic Manager-Profil zu verwenden, falls vorhanden. Traffic Manager-Ressourcen-ID wird von der Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</param>
        <param name="trafficManagerProfileName">Name des Traffic Manager-Profil zu erstellen. Dies ist nur erforderlich, wenn Traffic Manager-Profil nicht bereits vorhanden ist.</param>
        <param name="ignoreQuotas">&lt;Code&gt;"true"&lt;/code&gt; Wenn Kontingente ignoriert, andernfalls werden soll &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <summary>
            Initialisiert eine neue Instanz der CloningInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppSettingsOverrides">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; AppSettingsOverrides { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; AppSettingsOverrides" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.AppSettingsOverrides" />
      <MemberSignature Language="VB.NET" Value="Public Property AppSettingsOverrides As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.AppSettingsOverrides : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.AppSettingsOverrides" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appSettingsOverrides")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Anwendung Festlegen von Außerkraftsetzungen für die geklonte-app. Diese Einstellungen überschreiben, wenn angegeben, die Einstellungen aus der Quelle-app geklont. Andernfalls werden die Anwendungseinstellungen von Quell-app beibehalten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneCustomHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CloneCustomHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CloneCustomHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneCustomHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property CloneCustomHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CloneCustomHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneCustomHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloneCustomHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; benutzerdefinierte Hostnamen aus Quelle-app zu klonen, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp; Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneSourceControl">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CloneSourceControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CloneSourceControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CloneSourceControl As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CloneSourceControl : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneSourceControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloneSourceControl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Datenquellen-Steuerelement aus der Quelle-app zu klonen, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt ;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigureLoadBalancing">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ConfigureLoadBalancing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ConfigureLoadBalancing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.ConfigureLoadBalancing" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigureLoadBalancing As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ConfigureLoadBalancing : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.ConfigureLoadBalancing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configureLoadBalancing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So konfigurieren Sie einen Lastenausgleich für die Quelle und Ziel-app.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Korrelations-ID des klonprozesses. Diese ID verknüpft mehrere Klonvorgängen zusammen, um die gleichen Momentaufnahme zu verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die app Service-Umgebung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreQuotas">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.IgnoreQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreQuotas As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreQuotas : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.IgnoreQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Kontingente ignoriert, andernfalls werden soll &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Ziel-app; überschreiben, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceWebAppId">
      <MemberSignature Language="C#" Value="public string SourceWebAppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceWebAppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.SourceWebAppId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceWebAppId As String" />
      <MemberSignature Language="F#" Value="member this.SourceWebAppId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.SourceWebAppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceWebAppId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest ARM-Ressourcen-ID der Quelle-app. App-Ressourcen-ID, der die Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName ist} für produktionsslots und /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} für andere Steckplätze.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerProfileId">
      <MemberSignature Language="C#" Value="public string TrafficManagerProfileId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficManagerProfileId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileId" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficManagerProfileId As String" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerProfileId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="trafficManagerProfileId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ARM-Ressourcen-ID der Traffic Manager-Profil zu verwenden, falls vorhanden. Traffic Manager-Ressourcen-ID wird von der Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerProfileName">
      <MemberSignature Language="C#" Value="public string TrafficManagerProfileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficManagerProfileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficManagerProfileName As String" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerProfileName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="trafficManagerProfileName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Name des Traffic Manager-Profil zu erstellen. Dies ist nur erforderlich, wenn Traffic Manager-Profil nicht bereits vorhanden ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CloningInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloningInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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