<Type Name="Site" FullName="Microsoft.Azure.Management.WebSites.Models.Site">
  <TypeSignature Language="C#" Value="public class Site : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Site extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Site" />
  <TypeSignature Language="VB.NET" Value="Public Class Site&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Site = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine Web-app, einer mobilen app-Back-End- oder einer API-app.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Site ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Site.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Website-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Site (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string state = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, string repositorySiteName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; usageState = null, Nullable&lt;bool&gt; enabled = null, System.Collections.Generic.IList&lt;string&gt; enabledHostNames = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; availabilityState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; hostNameSslStates = null, string serverFarmId = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;DateTime&gt; lastModifiedTimeUtc = null, Microsoft.Azure.Management.WebSites.Models.SiteConfig siteConfig = null, System.Collections.Generic.IList&lt;string&gt; trafficManagerHostNames = null, Nullable&lt;bool&gt; scmSiteAlsoStopped = null, string targetSwapSlot = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, Nullable&lt;bool&gt; clientAffinityEnabled = null, Nullable&lt;bool&gt; clientCertEnabled = null, Nullable&lt;bool&gt; hostNamesDisabled = null, string outboundIpAddresses = null, string possibleOutboundIpAddresses = null, Nullable&lt;int&gt; containerSize = null, Nullable&lt;int&gt; dailyMemoryTimeQuota = null, Nullable&lt;DateTime&gt; suspendedTill = null, Nullable&lt;int&gt; maxNumberOfWorkers = null, Microsoft.Azure.Management.WebSites.Models.CloningInfo cloningInfo = null, Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest snapshotInfo = null, string resourceGroup = null, Nullable&lt;bool&gt; isDefaultContainer = null, string defaultHostName = null, Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus slotSwapStatus = null, Nullable&lt;bool&gt; httpsOnly = null, Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity identity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string state, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, string repositorySiteName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UsageState&gt; usageState, valuetype System.Nullable`1&lt;bool&gt; enabled, class System.Collections.Generic.IList`1&lt;string&gt; enabledHostNames, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; availabilityState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; hostNameSslStates, string serverFarmId, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTimeUtc, class Microsoft.Azure.Management.WebSites.Models.SiteConfig siteConfig, class System.Collections.Generic.IList`1&lt;string&gt; trafficManagerHostNames, valuetype System.Nullable`1&lt;bool&gt; scmSiteAlsoStopped, string targetSwapSlot, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, valuetype System.Nullable`1&lt;bool&gt; clientAffinityEnabled, valuetype System.Nullable`1&lt;bool&gt; clientCertEnabled, valuetype System.Nullable`1&lt;bool&gt; hostNamesDisabled, string outboundIpAddresses, string possibleOutboundIpAddresses, valuetype System.Nullable`1&lt;int32&gt; containerSize, valuetype System.Nullable`1&lt;int32&gt; dailyMemoryTimeQuota, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; suspendedTill, valuetype System.Nullable`1&lt;int32&gt; maxNumberOfWorkers, class Microsoft.Azure.Management.WebSites.Models.CloningInfo cloningInfo, class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest snapshotInfo, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; isDefaultContainer, string defaultHostName, class Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus slotSwapStatus, valuetype System.Nullable`1&lt;bool&gt; httpsOnly, class Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Site.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.UsageState},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HostNameSslState},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},Microsoft.Azure.Management.WebSites.Models.SiteConfig,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.WebSites.Models.CloningInfo,Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus,System.Nullable{System.Boolean},Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Site : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.WebSites.Models.SiteConfig * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.WebSites.Models.CloningInfo * Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus * Nullable&lt;bool&gt; * Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity -&gt; Microsoft.Azure.Management.WebSites.Models.Site" Usage="new Microsoft.Azure.Management.WebSites.Models.Site (location, id, name, kind, type, tags, state, hostNames, repositorySiteName, usageState, enabled, enabledHostNames, availabilityState, hostNameSslStates, serverFarmId, reserved, lastModifiedTimeUtc, siteConfig, trafficManagerHostNames, scmSiteAlsoStopped, targetSwapSlot, hostingEnvironmentProfile, clientAffinityEnabled, clientCertEnabled, hostNamesDisabled, outboundIpAddresses, possibleOutboundIpAddresses, containerSize, dailyMemoryTimeQuota, suspendedTill, maxNumberOfWorkers, cloningInfo, snapshotInfo, resourceGroup, isDefaultContainer, defaultHostName, slotSwapStatus, httpsOnly, identity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="repositorySiteName" Type="System.String" />
        <Parameter Name="usageState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availabilityState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;" />
        <Parameter Name="hostNameSslStates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt;" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastModifiedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfig" Type="Microsoft.Azure.Management.WebSites.Models.SiteConfig" />
        <Parameter Name="trafficManagerHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="scmSiteAlsoStopped" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetSwapSlot" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="clientAffinityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clientCertEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostNamesDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outboundIpAddresses" Type="System.String" />
        <Parameter Name="possibleOutboundIpAddresses" Type="System.String" />
        <Parameter Name="containerSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dailyMemoryTimeQuota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="suspendedTill" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cloningInfo" Type="Microsoft.Azure.Management.WebSites.Models.CloningInfo" />
        <Parameter Name="snapshotInfo" Type="Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="isDefaultContainer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultHostName" Type="System.String" />
        <Parameter Name="slotSwapStatus" Type="Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" />
        <Parameter Name="httpsOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity" />
      </Parameters>
      <Docs>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="state">Aktuellen Status der app.</param>
        <param name="hostNames">Die Hostnamen der app zugeordnet haben.</param>
        <param name="repositorySiteName">Name der Repository-Website.</param>
        <param name="usageState">Status, der angibt, ob die app die quotenauslastung überschritten hat. Schreibgeschützt. Folgende Werte sind möglich: 'Normal', "Wurde überschritten"</param>
        <param name="enabled">&lt;Code&gt;"true"&lt;/code&gt; ist die app aktiviert ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;. Wenn dieser Wert auf "false" wird die app (die app offline geschaltet) deaktiviert.</param>
        <param name="enabledHostNames">Aktivierte Hostnamen für die app. Hostnamen müssen zugewiesen werden (Siehe Hostnamen) und aktiviert.
            Andernfalls wird die app nicht auf diesen Hostnamen verarbeitet.</param>
        <param name="availabilityState">Management Informationen den Verfügbarkeitsstatus für die app. Folgende Werte sind möglich: 'Normal', "Limited", "DisasterRecoveryMode"</param>
        <param name="hostNameSslStates">Hostname-SSL-Status werden verwendet, um die SSL-Bindungen für app Hostnamen verwalten.</param>
        <param name="serverFarmId">Ressourcen-ID des zugeordneten App Service-Plans formatiert: "/ subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</param>
        <param name="reserved">&lt;Code&gt;"true"&lt;/code&gt; Wenn reserviert ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="lastModifiedTimeUtc">Letzte Änderung die app, in UTC angegeben wurde. Schreibgeschützt.</param>
        <param name="siteConfig">Konfiguration der app.</param>
        <param name="trafficManagerHostNames">Azure Traffic Manager Hostnamen, die der app zugeordnet ist. Schreibgeschützt.</param>
        <param name="scmSiteAlsoStopped">&lt;Code&gt;"true"&lt;/code&gt; SCM (KUDU) Website beenden, wenn die app beendet ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;. Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="targetSwapSlot">Gibt an, welche bereitstellungsslot in dieser app auslagern. Schreibgeschützt.</param>
        <param name="hostingEnvironmentProfile">App Service-Umgebung für die app zu verwenden.</param>
        <param name="clientAffinityEnabled">&lt;Code&gt;"true"&lt;/code&gt; So aktivieren Sie die Clientaffinität; &lt;Code&gt;"false"&lt;/code&gt; senden Session Affinity Cookies Weiterleiten von Clientanforderungen in derselben Sitzung an dieselbe Instanz beendet werden soll. Standardmäßig wird &lt;Code&gt;"true"&lt;/code&gt;.</param>
        <param name="clientCertEnabled">&lt;Code&gt;"true"&lt;/code&gt; So aktivieren Sie die Clientzertifikatauthentifizierung (TLS gegenseitige Authentifizierung); andernfalls &lt;Code&gt;"false"&lt;/code&gt;. Standardmäßig wird &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="hostNamesDisabled">&lt;Code&gt;"true"&lt;/code&gt; So deaktivieren Sie den öffentlichen Hostnamen der app; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.
            Wenn &lt;Code&gt;"true"&lt;/code&gt;, die app ist nur über API Management-Prozesses zugegriffen werden kann.</param>
        <param name="outboundIpAddresses">Liste der IP-Adressen, die die app für ausgehende Verbindungen (z. B. Datenbankzugriff) verwendet. Enthält die virtuellen IP-Adressen von Mandanten diesen Standort gehostet werden kann, mit der aktuellen Einstellungen.
            Schreibgeschützt.</param>
        <param name="possibleOutboundIpAddresses">Liste der IP-Adressen, die die app für ausgehende Verbindungen (z. B. Datenbankzugriff) verwendet.
            Schließt VIPs von allen Mandanten an. Schreibgeschützt.</param>
        <param name="containerSize">Die Größe des Containers Funktion.</param>
        <param name="dailyMemoryTimeQuota">Maximal zulässige Arbeitsspeicher-Time-tageskontingent (gilt für nur dynamische apps).</param>
        <param name="suspendedTill">App bis zum angehalten wird, für den Fall, dass Arbeitsspeicher Laufzeit überschritten wird.</param>
        <param name="maxNumberOfWorkers">Maximale Anzahl von Arbeitsthreads.
            Dies gilt nur für Funktionen Container.</param>
        <param name="cloningInfo">Wenn während der Erstellung der app angegeben, wird die app aus einer Quelle-app geklont.</param>
        <param name="snapshotInfo">Wenn während der Erstellung der app angegeben, wird die app aus einem früheren Momentaufnahme erstellt.</param>
        <param name="resourceGroup">Name der Ressourcengruppe, die app gehört. Schreibgeschützt.</param>
        <param name="isDefaultContainer">&lt;Code&gt;"true"&lt;/code&gt; ist die app einen Standardcontainer; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="defaultHostName">Standard-Hostname der app.
            Schreibgeschützt.</param>
        <param name="slotSwapStatus">Status der letzten Bereitstellung Slot Swap-Vorgang.</param>
        <param name="httpsOnly">HttpsOnly: konfiguriert eine Website, um ausschließlich Https-Anforderungen zu akzeptieren. Probleme Umleitung für HTTP-Anforderungen</param>
        <param name="identity">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der Website-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt; AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As Nullable(Of SiteAvailabilityState)" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteAvailabilityState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Verfügbarkeitsstatus für Management-Informationen für die app ab.
            Folgende Werte sind möglich: 'Normal', "Limited", "DisasterRecoveryMode"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientAffinityEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientAffinityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientAffinityEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So aktivieren Sie die Clientaffinität; &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; Senden Session Affinity Cookies Weiterleiten von Clientanforderungen in derselben Sitzung an dieselbe Instanz beendet werden soll. Standardmäßig wird &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientCertEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So aktivieren Sie die Clientzertifikatauthentifizierung (TLS gegenseitige Authentifizierung); andernfalls &amp;Lt; Code&amp;Gt; "false"&amp;Lt; / code&amp;Gt;. Standardmäßig wird &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CloningInfo CloningInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.WebSites.Models.CloningInfo with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloningInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der angegebene während der Erstellung der app, die app aus einer Quelle-app geklont.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ContainerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe des Containers Funktion fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMemoryTimeQuota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DailyMemoryTimeQuota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DailyMemoryTimeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.DailyMemoryTimeQuota" />
      <MemberSignature Language="VB.NET" Value="Public Property DailyMemoryTimeQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DailyMemoryTimeQuota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.DailyMemoryTimeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dailyMemoryTimeQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest maximale tageskontingent Arbeitsspeicher-Time (gilt für nur dynamische apps) zulässig.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Standard-Hostname der app. Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die app, aktiviert ist, andernfalls ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;. Wenn dieser Wert auf "false" wird die app (die app offline geschaltet) deaktiviert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabledHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das aktivierte Hostnamen für die app. Hostnamen müssen zugewiesen werden (Siehe Hostnamen) und aktiviert. Andernfalls wird die app nicht auf diesen Hostnamen verarbeitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest app Service-Umgebung für die app zu verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Hostnamen der app zugeordnet haben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HostNamesDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNamesDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNamesDisabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; deaktivieren Sie den öffentlichen Hostnamen der app; andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp; Gt;.
            Wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; die app ist nur über API Management-Prozesses zugegriffen werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; HostNameSslStates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameSslStates As IList(Of HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameSslStates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Hostname SSL Zustände werden verwendet, um die SSL-Bindungen für app Hostnamen verwalten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HttpsOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HttpsOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.HttpsOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpsOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HttpsOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.HttpsOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpsOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest HttpsOnly: konfiguriert eine Website, um ausschließlich Https-Anforderungen zu akzeptieren. Probleme Umleitung für HTTP-Anforderungen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As ManagedServiceIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ManagedServiceIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDefaultContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die app eine standardentitätscontainer ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.LastModifiedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.LastModifiedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die letzten, an die app in UTC geändert wurde. Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.MaxNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.MaxNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Anzahl von Arbeitsthreads.
            Dies gilt nur für Funktionen Container.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string OutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der IP-Adressen, die die app für ausgehende Verbindungen (z. B. Datenbankzugriff) verwendet. Enthält die virtuellen IP-Adressen von Mandanten diesen Standort gehostet werden kann, mit der aktuellen Einstellungen. Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PossibleOutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string PossibleOutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PossibleOutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.PossibleOutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PossibleOutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.PossibleOutboundIpAddresses : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.PossibleOutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.possibleOutboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der IP-Adressen, die die app für ausgehende Verbindungen (z. B. Datenbankzugriff) verwendet. Schließt VIPs von allen Mandanten an.
            Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.repositorySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Repository-Website ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reserved")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn reserviert ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Namen der Ressourcengruppe, zu der die app gehört. Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ScmSiteAlsoStopped { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmSiteAlsoStopped As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scmSiteAlsoStopped")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; SCM (KUDU) Website beenden, wenn die app beendet ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;. Die Standardeinstellung ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest des zugehörigen App Service-Plans, formatiert als Ressourcen-ID: "/ subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SiteConfig SiteConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SiteConfig SiteConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SiteConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteConfig As SiteConfig" />
      <MemberSignature Language="F#" Value="member this.SiteConfig : Microsoft.Azure.Management.WebSites.Models.SiteConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SiteConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SiteConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration der app fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlotSwapStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus SlotSwapStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus SlotSwapStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SlotSwapStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotSwapStatus As SlotSwapStatus" />
      <MemberSignature Language="F#" Value="member this.SlotSwapStatus : Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SlotSwapStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.slotSwapStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SlotSwapStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status der letzten Bereitstellung Slot Swap-Vorgang ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest SnapshotInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest SnapshotInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SnapshotInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotInfo As SnapshotRecoveryRequest" />
      <MemberSignature Language="F#" Value="member this.SnapshotInfo : Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SnapshotInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.snapshotInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SnapshotRecoveryRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob während der Erstellung der app angegeben, wird die app aus einem früheren Momentaufnahme erstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Status der app ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendedTill">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SuspendedTill { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SuspendedTill" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.SuspendedTill" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuspendedTill As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SuspendedTill : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.SuspendedTill" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspendedTill")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die app, die bis zum angehalten wird, für den Fall, dass Arbeitsspeicher Laufzeit überschritten wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.WebSites.Models.Site.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetSwapSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt an, welche bereitstellungsslot in dieser app auslagern.
            Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficManagerHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Azure Traffic Manager-Hostnamen der app zugeordnet haben.
            Schreibgeschützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt; UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UsageState&gt; UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Site.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As Nullable(Of UsageState)" />
      <MemberSignature Language="F#" Value="member this.UsageState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Site.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UsageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Zustand, der angibt, ob die app die quotenauslastung überschritten hat.
            Schreibgeschützt. Folgende Werte sind möglich: 'Normal', "Wurde überschritten"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Site.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="site.Validate " />
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