<Type Name="SiteExtensionInfo" FullName="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo">
  <TypeSignature Language="C#" Value="public class SiteExtensionInfo : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteExtensionInfo extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteExtensionInfo&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteExtensionInfo = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Erweiterung Standortinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteExtensionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SiteExtensionInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteExtensionInfo (string id = null, string name = null, string kind = null, string type = null, string siteExtensionInfoId = null, string title = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt; siteExtensionInfoType = null, string summary = null, string description = null, string version = null, string extensionUrl = null, string projectUrl = null, string iconUrl = null, string licenseUrl = null, string feedUrl = null, System.Collections.Generic.IList&lt;string&gt; authors = null, string installationArgs = null, Nullable&lt;DateTime&gt; publishedDateTime = null, Nullable&lt;int&gt; downloadCount = null, Nullable&lt;bool&gt; localIsLatestVersion = null, string localPath = null, Nullable&lt;DateTime&gt; installedDateTime = null, string provisioningState = null, string comment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string siteExtensionInfoId, string title, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt; siteExtensionInfoType, string summary, string description, string version, string extensionUrl, string projectUrl, string iconUrl, string licenseUrl, string feedUrl, class System.Collections.Generic.IList`1&lt;string&gt; authors, string installationArgs, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; publishedDateTime, valuetype System.Nullable`1&lt;int32&gt; downloadCount, valuetype System.Nullable`1&lt;bool&gt; localIsLatestVersion, string localPath, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; installedDateTime, string provisioningState, string comment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.SiteExtensionType},System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{System.DateTime},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional siteExtensionInfoId As String = null, Optional title As String = null, Optional siteExtensionInfoType As Nullable(Of SiteExtensionType) = null, Optional summary As String = null, Optional description As String = null, Optional version As String = null, Optional extensionUrl As String = null, Optional projectUrl As String = null, Optional iconUrl As String = null, Optional licenseUrl As String = null, Optional feedUrl As String = null, Optional authors As IList(Of String) = null, Optional installationArgs As String = null, Optional publishedDateTime As Nullable(Of DateTime) = null, Optional downloadCount As Nullable(Of Integer) = null, Optional localIsLatestVersion As Nullable(Of Boolean) = null, Optional localPath As String = null, Optional installedDateTime As Nullable(Of DateTime) = null, Optional provisioningState As String = null, Optional comment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt; * string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo (id, name, kind, type, siteExtensionInfoId, title, siteExtensionInfoType, summary, description, version, extensionUrl, projectUrl, iconUrl, licenseUrl, feedUrl, authors, installationArgs, publishedDateTime, downloadCount, localIsLatestVersion, localPath, installedDateTime, provisioningState, comment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="siteExtensionInfoId" Type="System.String" />
        <Parameter Name="title" Type="System.String" />
        <Parameter Name="siteExtensionInfoType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt;" />
        <Parameter Name="summary" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="extensionUrl" Type="System.String" />
        <Parameter Name="projectUrl" Type="System.String" />
        <Parameter Name="iconUrl" Type="System.String" />
        <Parameter Name="licenseUrl" Type="System.String" />
        <Parameter Name="feedUrl" Type="System.String" />
        <Parameter Name="authors" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="installationArgs" Type="System.String" />
        <Parameter Name="publishedDateTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="downloadCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="localIsLatestVersion" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="localPath" Type="System.String" />
        <Parameter Name="installedDateTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="comment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="siteExtensionInfoId">Website-Erweiterungs-ID.</param>
        <param name="title">Titel der Website-Erweiterung.</param>
        <param name="siteExtensionInfoType">Typ der Erweiterung des Standorts. Folgende Werte sind möglich: "Katalog", "WebRoot"</param>
        <param name="summary">Zusammenfassende Beschreibung.</param>
        <param name="description">Detaillierte Beschreibung.</param>
        <param name="version">Versionsinformationen.</param>
        <param name="extensionUrl">URL der Erweiterung.</param>
        <param name="projectUrl">Projekt-URL.</param>
        <param name="iconUrl">Symbol-URL.</param>
        <param name="licenseUrl">Lizenz-URL.</param>
        <param name="feedUrl">Feed-URL.</param>
        <param name="authors">Liste der Autoren.</param>
        <param name="installationArgs">Installer Befehlszeilenparameter enthalten.</param>
        <param name="publishedDateTime">Veröffentlichte Zeitstempel.</param>
        <param name="downloadCount">Die Anzahl der Downloads.</param>
        <param name="localIsLatestVersion">&lt;Code&gt;"true"&lt;/code&gt; ist die lokale Version die aktuellste Version; &lt;Code&gt;"false"&lt;/code&gt; andernfalls.</param>
        <param name="localPath">Lokaler Pfad.</param>
        <param name="installedDateTime">Installierte Zeitstempel.</param>
        <param name="provisioningState">Der Bereitstellungsstatus.</param>
        <param name="comment">Site-Erweiterung Kommentar.</param>
        <summary>
            Initialisiert eine neue Instanz der SiteExtensionInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Authors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Authors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Authors" />
      <MemberSignature Language="VB.NET" Value="Public Property Authors As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Authors : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Authors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Autoren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Comment">
      <MemberSignature Language="C#" Value="public string Comment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Comment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Comment" />
      <MemberSignature Language="VB.NET" Value="Public Property Comment As String" />
      <MemberSignature Language="F#" Value="member this.Comment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Comment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.comment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Standort Erweiterung Kommentar.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            Ruft ab, oder legt die ausführliche Beschreibung fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DownloadCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DownloadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.DownloadCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DownloadCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DownloadCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.DownloadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.downloadCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Downloads.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionUrl">
      <MemberSignature Language="C#" Value="public string ExtensionUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtensionUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.ExtensionUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionUrl As String" />
      <MemberSignature Language="F#" Value="member this.ExtensionUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.ExtensionUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.extensionUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Erweiterung URL.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FeedUrl">
      <MemberSignature Language="C#" Value="public string FeedUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FeedUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.FeedUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property FeedUrl As String" />
      <MemberSignature Language="F#" Value="member this.FeedUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.FeedUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.feedUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt feed-URL.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IconUrl">
      <MemberSignature Language="C#" Value="public string IconUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IconUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.IconUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property IconUrl As String" />
      <MemberSignature Language="F#" Value="member this.IconUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.IconUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.iconUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Symbol-URL.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallationArgs">
      <MemberSignature Language="C#" Value="public string InstallationArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstallationArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.InstallationArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property InstallationArgs As String" />
      <MemberSignature Language="F#" Value="member this.InstallationArgs : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.InstallationArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.installationArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Installer Befehlszeilenparameter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstalledDateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; InstalledDateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; InstalledDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.InstalledDateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property InstalledDateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.InstalledDateTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.InstalledDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.installedDateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt installiert Zeitstempel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseUrl">
      <MemberSignature Language="C#" Value="public string LicenseUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.LicenseUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseUrl As String" />
      <MemberSignature Language="F#" Value="member this.LicenseUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.LicenseUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.licenseUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Lizenz-URL.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIsLatestVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LocalIsLatestVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LocalIsLatestVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.LocalIsLatestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIsLatestVersion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LocalIsLatestVersion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.LocalIsLatestVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localIsLatestVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; ist die lokale Version die aktuellste Version; &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt andernfalls.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPath">
      <MemberSignature Language="C#" Value="public string LocalPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.LocalPath" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPath As String" />
      <MemberSignature Language="F#" Value="member this.LocalPath : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.LocalPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokalen Pfad.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProjectUrl">
      <MemberSignature Language="C#" Value="public string ProjectUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProjectUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.ProjectUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ProjectUrl As String" />
      <MemberSignature Language="F#" Value="member this.ProjectUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.ProjectUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.projectUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Projekt-URL.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft ab, oder legt sie fest, der Bereitstellungsstatus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishedDateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PublishedDateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PublishedDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.PublishedDateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishedDateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PublishedDateTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.PublishedDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishedDateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest veröffentlichten Zeitstempel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteExtensionInfoId">
      <MemberSignature Language="C#" Value="public string SiteExtensionInfoId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteExtensionInfoId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.SiteExtensionInfoId" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteExtensionInfoId As String" />
      <MemberSignature Language="F#" Value="member this.SiteExtensionInfoId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.SiteExtensionInfoId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Standort Erweiterungs-ID.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteExtensionInfoType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt; SiteExtensionInfoType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt; SiteExtensionInfoType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.SiteExtensionInfoType" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteExtensionInfoType As Nullable(Of SiteExtensionType)" />
      <MemberSignature Language="F#" Value="member this.SiteExtensionInfoType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.SiteExtensionInfoType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SiteExtensionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Standort Erweiterungstyp. Folgende Werte sind möglich: "Katalog", "WebRoot"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Summary">
      <MemberSignature Language="C#" Value="public string Summary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Summary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Summary" />
      <MemberSignature Language="VB.NET" Value="Public Property Summary As String" />
      <MemberSignature Language="F#" Value="member this.Summary : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Summary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.summary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die zusammenfassungsbeschreibung fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.title")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Titel der Website-Erweiterung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteExtensionInfo.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Version.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>