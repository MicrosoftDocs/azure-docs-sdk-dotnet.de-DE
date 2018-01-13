<Type Name="DatabaseSecurityAlertPolicy" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy">
  <TypeSignature Language="C#" Value="public class DatabaseSecurityAlertPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseSecurityAlertPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseSecurityAlertPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DatabaseSecurityAlertPolicy = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Enthält Informationen über eine Richtlinie für die Bedrohungserkennung-Datenbank.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseSecurityAlertPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DatabaseSecurityAlertPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseSecurityAlertPolicy (Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState state, string id = null, string name = null, string type = null, string location = null, string kind = null, string disabledAlerts = null, string emailAddresses = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; emailAccountAdmins = null, string storageEndpoint = null, string storageAccountAccessKey = null, Nullable&lt;int&gt; retentionDays = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; useServerDefault = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState state, string id, string name, string type, string location, string kind, string disabledAlerts, string emailAddresses, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; emailAccountAdmins, string storageEndpoint, string storageAccountAccessKey, valuetype System.Nullable`1&lt;int32&gt; retentionDays, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; useServerDefault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins},System.String,System.String,System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As SecurityAlertPolicyState, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional kind As String = null, Optional disabledAlerts As String = null, Optional emailAddresses As String = null, Optional emailAccountAdmins As Nullable(Of SecurityAlertPolicyEmailAccountAdmins) = null, Optional storageEndpoint As String = null, Optional storageAccountAccessKey As String = null, Optional retentionDays As Nullable(Of Integer) = null, Optional useServerDefault As Nullable(Of SecurityAlertPolicyUseServerDefault) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy : Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState * string * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy (state, id, name, type, location, kind, disabledAlerts, emailAddresses, emailAccountAdmins, storageEndpoint, storageAccountAccessKey, retentionDays, useServerDefault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="disabledAlerts" Type="System.String" />
        <Parameter Name="emailAddresses" Type="System.String" />
        <Parameter Name="emailAccountAdmins" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt;" />
        <Parameter Name="storageEndpoint" Type="System.String" />
        <Parameter Name="storageAccountAccessKey" Type="System.String" />
        <Parameter Name="retentionDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useServerDefault" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt;" />
      </Parameters>
      <Docs>
        <param name="state">Gibt den Status der Richtlinie. Wenn der Status aktiviert ist, sind StorageEndpoint und StorageAccountAccessKey erforderlich.
            Folgende Werte sind möglich: "New", "Aktiviert", "Deaktiviert"</param>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="location">Der geografische Standort, in dem die Ressource aktiv ist</param>
        <param name="kind">Ressourcenart.</param>
        <param name="disabledAlerts">Gibt an, die durch Semikolons getrennte Liste der Warnungen, die deaktiviert sind, oder eine leere Zeichenfolge, die keine Warnungen zu deaktivieren.
            Mögliche Werte: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</param>
        <param name="emailAddresses">Gibt die durch Semikolons getrennte Liste der e-Mail-Adressen, die an denen die Warnung gesendet wird.</param>
        <param name="emailAccountAdmins">Gibt an, dass die Warnung für die Kontoadministratoren gesendet wird. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="storageEndpoint">Gibt den Blob-speicherendpunkt (z. B. https://MyAccount.blob.core.windows.net) an. Alle Bedrohungserkennung Überwachungsprotokolle, dieses Blob-Speicher gespeichert werden. Wenn der Status aktiviert ist, ist die StorageEndpoint erforderlich.</param>
        <param name="storageAccountAccessKey">Gibt den bezeichnerschlüssel des Speicherkontos für die Bedrohungserkennung überwachen. Wenn der Status aktiviert ist, ist die StorageAccountAccessKey erforderlich.</param>
        <param name="retentionDays">Gibt die Anzahl der Tage, die in den Überwachungsprotokollen für die Erkennung von Bedrohungen zu halten.</param>
        <param name="useServerDefault">Gibt an, ob die Standardrichtlinie für Server verwenden. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <summary>
            Initialisiert eine neue Instanz der DatabaseSecurityAlertPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledAlerts">
      <MemberSignature Language="C#" Value="public string DisabledAlerts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisabledAlerts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.DisabledAlerts" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledAlerts As String" />
      <MemberSignature Language="F#" Value="member this.DisabledAlerts : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.DisabledAlerts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disabledAlerts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, die durch Semikolons getrennte Liste der Warnungen, die deaktiviert sind, oder eine leere Zeichenfolge, die keine Warnungen zu deaktivieren. Mögliche Werte: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAccountAdmins">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; EmailAccountAdmins { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; EmailAccountAdmins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAccountAdmins" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAccountAdmins As Nullable(Of SecurityAlertPolicyEmailAccountAdmins)" />
      <MemberSignature Language="F#" Value="member this.EmailAccountAdmins : Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAccountAdmins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailAccountAdmins")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, dass die Warnung für die Kontoadministratoren gesendet wird. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddresses">
      <MemberSignature Language="C#" Value="public string EmailAddresses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAddresses" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddresses As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddresses : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, die durch Semikolons getrennte Liste der e-Mail-Adressen, die an den die Warnung gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ressourcenart ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den geografischen Standort aktiv ist, in dem die Ressource
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.RetentionDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.RetentionDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest gibt die Anzahl der Tage, in den Überwachungsprotokollen für die Erkennung von Bedrohungen zu halten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As SecurityAlertPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Status der Richtlinie an. Wenn der Status aktiviert ist, sind StorageEndpoint und StorageAccountAccessKey erforderlich.
            Folgende Werte sind möglich: "New", "Aktiviert", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountAccessKey">
      <MemberSignature Language="C#" Value="public string StorageAccountAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageAccountAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountAccessKey : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageAccountAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountAccessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest gibt den bezeichnerschlüssel des Speicherkontos für die Bedrohungserkennung Überwachung an. Wenn der Status aktiviert ist, ist die StorageAccountAccessKey erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageEndpoint">
      <MemberSignature Language="C#" Value="public string StorageEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.StorageEndpoint : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt der Blob-speicherendpunkt (z. B. https://MyAccount.blob.core.windows.net) an. Alle Bedrohungserkennung Überwachungsprotokolle, dieses Blob-Speicher gespeichert werden. Wenn der Status aktiviert ist, ist die StorageEndpoint erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseServerDefault">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; UseServerDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; UseServerDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.UseServerDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property UseServerDefault As Nullable(Of SecurityAlertPolicyUseServerDefault)" />
      <MemberSignature Language="F#" Value="member this.UseServerDefault : Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.UseServerDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.useServerDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob die Standardrichtlinie für Server verwenden, ruft ab oder legt ihn fest.
            Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="databaseSecurityAlertPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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