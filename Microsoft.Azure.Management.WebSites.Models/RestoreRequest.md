<Type Name="RestoreRequest" FullName="Microsoft.Azure.Management.WebSites.Models.RestoreRequest">
  <TypeSignature Language="C#" Value="public class RestoreRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestoreRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RestoreRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class RestoreRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type RestoreRequest = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibung der eine Anforderung zum Wiederherstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RestoreRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequest (string id = null, string name = null, string kind = null, string type = null, string storageAccountUrl = null, string blobName = null, Nullable&lt;bool&gt; overwrite = null, string siteName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;bool&gt; ignoreConflictingHostNames = null, Nullable&lt;bool&gt; ignoreDatabases = null, string appServicePlan = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; operationType = null, Nullable&lt;bool&gt; adjustConnectionStrings = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string storageAccountUrl, string blobName, valuetype System.Nullable`1&lt;bool&gt; overwrite, string siteName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;bool&gt; ignoreConflictingHostNames, valuetype System.Nullable`1&lt;bool&gt; ignoreDatabases, string appServicePlan, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; operationType, valuetype System.Nullable`1&lt;bool&gt; adjustConnectionStrings, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional storageAccountUrl As String = null, Optional blobName As String = null, Optional overwrite As Nullable(Of Boolean) = null, Optional siteName As String = null, Optional databases As IList(Of DatabaseBackupSetting) = null, Optional ignoreConflictingHostNames As Nullable(Of Boolean) = null, Optional ignoreDatabases As Nullable(Of Boolean) = null, Optional appServicePlan As String = null, Optional operationType As Nullable(Of BackupRestoreOperationType) = null, Optional adjustConnectionStrings As Nullable(Of Boolean) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RestoreRequest : string * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.RestoreRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.RestoreRequest (id, name, kind, type, storageAccountUrl, blobName, overwrite, siteName, databases, ignoreConflictingHostNames, ignoreDatabases, appServicePlan, operationType, adjustConnectionStrings, hostingEnvironment)" />
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
        <Parameter Name="storageAccountUrl" Type="System.String" />
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="ignoreConflictingHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ignoreDatabases" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appServicePlan" Type="System.String" />
        <Parameter Name="operationType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;" />
        <Parameter Name="adjustConnectionStrings" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="storageAccountUrl">SAS-URL für den Container.</param>
        <param name="blobName">Der Name eines BLOB, das die Sicherung enthält.</param>
        <param name="overwrite">&lt;Code&gt;"true"&lt;/code&gt; Ziel-app; der Restore-Vorgang überschrieben werden kann, andernfalls &lt;Code&gt;"false"&lt;/code&gt;. &lt;Code&gt;"true"&lt;/code&gt; ist erforderlich, wenn Sie versuchen, über eine vorhandene app wiederherzustellen.</param>
        <param name="siteName">Der Name einer app.</param>
        <param name="databases">Auflistung von Datenbanken, die wiederhergestellt werden soll. Diese Liste muss die Liste der Datenbanken, die in der Sicherung überein.</param>
        <param name="ignoreConflictingHostNames">Ändert eine Logik, beim Wiederherstellen einer Apps mit benutzerdefinierten Domänen. &lt;Code&gt;"true"&lt;/code&gt; benutzerdefinierte Domänen automatisch zu entfernen. Wenn &lt;Code&gt;"false"&lt;/code&gt;, benutzerdefinierte Domänen werden in der app-Objekt hinzugefügt, wenn wird wiederhergestellt, sondern, die möglicherweise kann aufgrund von Konflikten während des Vorgangs.</param>
        <param name="ignoreDatabases">Ignorieren Sie die Datenbanken und sollten nur dann Wiederherstellen des Websiteinhalts</param>
        <param name="appServicePlan">Geben Sie die app Service-Plan, der wiederhergestellte Standort besitzen wird.</param>
        <param name="operationType">Vorgangstyp. Folgende Werte sind möglich: "Default", "Klonen", "Verschieben", "Snapshot"</param>
        <param name="adjustConnectionStrings">&lt;Code&gt;"true"&lt;/code&gt; Wenn SiteConfig.ConnectionStrings in neue app; festgelegt werden soll, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="hostingEnvironment">App-Name Service-Umgebung, wenn (nur erforderlich, wenn eine app auf einer App Service-Umgebung wiederhergestellt wird).</param>
        <summary>
            Initialisiert eine neue Instanz der RestoreRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdjustConnectionStrings">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdjustConnectionStrings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdjustConnectionStrings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AdjustConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Property AdjustConnectionStrings As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdjustConnectionStrings : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AdjustConnectionStrings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adjustConnectionStrings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn SiteConfig.ConnectionStrings in neue app; festgelegt werden soll, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code &amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlan">
      <MemberSignature Language="C#" Value="public string AppServicePlan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServicePlan As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlan : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AppServicePlan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appServicePlan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Geben Sie app Service-Plan, der wiederhergestellte Standort besitzen wird, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobName">
      <MemberSignature Language="C#" Value="public string BlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.BlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobName As String" />
      <MemberSignature Language="F#" Value="member this.BlobName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.BlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Name eines BLOB, das die Sicherung enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung von Datenbanken, die wiederhergestellt werden soll. Diese Liste muss die Liste der Datenbanken, die in der Sicherung überein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie Name des app Service-Umgebung, fest, wenn (nur erforderlich, wenn eine app auf einer App Service-Umgebung wiederhergestellt wird).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreConflictingHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreConflictingHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreConflictingHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreConflictingHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreConflictingHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreConflictingHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreConflictingHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreConflictingHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest Änderungen eine Logik beim Wiederherstellen einer Apps mit benutzerdefinierten Domänen. &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; um benutzerdefinierte Domänen automatisch zu entfernen. Wenn &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; benutzerdefinierte Domänen werden in der app-Objekt hinzugefügt, wenn wird wiederhergestellt, sondern, die möglicherweise kann aufgrund von Konflikten während des Vorgangs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreDatabases">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreDatabases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreDatabases As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreDatabases : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreDatabases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ignorieren die Datenbanken und sollten nur dann wiederherstellen den Websiteinhalt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; OperationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationType As Nullable(Of BackupRestoreOperationType)" />
      <MemberSignature Language="F#" Value="member this.OperationType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Vorgang. Folgende Werte sind möglich: "Default", "Klonen", "Verschieben", "Snapshot"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Ziel-app; der Restore-Vorgang überschrieben werden kann, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.
            &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; ist erforderlich, wenn Sie versuchen, über eine vorhandene app wiederherzustellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen einer App fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.StorageAccountUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die SAS-URL auf den Container fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>