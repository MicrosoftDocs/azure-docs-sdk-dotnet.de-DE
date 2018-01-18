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
            <span data-ttu-id="44d26-101">Enthält Informationen über eine Richtlinie für die Bedrohungserkennung-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="44d26-101">Contains information about a database Threat Detection policy.</span></span>
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
            <span data-ttu-id="44d26-102">Initialisiert eine neue Instanz der DatabaseSecurityAlertPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="44d26-102">Initializes a new instance of the DatabaseSecurityAlertPolicy class.</span></span>
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
        <param name="state"><span data-ttu-id="44d26-103">Gibt den Status der Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="44d26-103">Specifies the state of the policy.</span></span> <span data-ttu-id="44d26-104">Wenn der Status aktiviert ist, sind StorageEndpoint und StorageAccountAccessKey erforderlich.</span><span class="sxs-lookup"><span data-stu-id="44d26-104">If state is Enabled, storageEndpoint and storageAccountAccessKey are required.</span></span>
            <span data-ttu-id="44d26-105">Folgende Werte sind möglich: "New", "Aktiviert", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="44d26-105">Possible values include: 'New', 'Enabled', 'Disabled'</span></span></param>
        <param name="id"><span data-ttu-id="44d26-106">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="44d26-106">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="44d26-107">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="44d26-107">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="44d26-108">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="44d26-108">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="44d26-109">Der geografische Standort, in dem die Ressource aktiv ist</span><span class="sxs-lookup"><span data-stu-id="44d26-109">The geo-location where the resource lives</span></span></param>
        <param name="kind"><span data-ttu-id="44d26-110">Ressourcenart.</span><span class="sxs-lookup"><span data-stu-id="44d26-110">Resource kind.</span></span></param>
        <param name="disabledAlerts"><span data-ttu-id="44d26-111">Gibt an, die durch Semikolons getrennte Liste der Warnungen, die deaktiviert sind, oder eine leere Zeichenfolge, die keine Warnungen zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="44d26-111">Specifies the semicolon-separated list of alerts that are disabled, or empty string to disable no alerts.</span></span>
            <span data-ttu-id="44d26-112">Mögliche Werte: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</span><span class="sxs-lookup"><span data-stu-id="44d26-112">Possible values: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</span></span></param>
        <param name="emailAddresses"><span data-ttu-id="44d26-113">Gibt die durch Semikolons getrennte Liste der e-Mail-Adressen, die an denen die Warnung gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="44d26-113">Specifies the semicolon-separated list of e-mail addresses to which the alert is sent.</span></span></param>
        <param name="emailAccountAdmins"><span data-ttu-id="44d26-114">Gibt an, dass die Warnung für die Kontoadministratoren gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="44d26-114">Specifies that the alert is sent to the account administrators.</span></span> <span data-ttu-id="44d26-115">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="44d26-115">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="storageEndpoint"><span data-ttu-id="44d26-116">Gibt den Blob-speicherendpunkt (z. B. https://MyAccount.blob.core.windows.net) an.</span><span class="sxs-lookup"><span data-stu-id="44d26-116">Specifies the blob storage endpoint (e.g. https://MyAccount.blob.core.windows.net).</span></span> <span data-ttu-id="44d26-117">Alle Bedrohungserkennung Überwachungsprotokolle, dieses Blob-Speicher gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="44d26-117">This blob storage will hold all Threat Detection audit logs.</span></span> <span data-ttu-id="44d26-118">Wenn der Status aktiviert ist, ist die StorageEndpoint erforderlich.</span><span class="sxs-lookup"><span data-stu-id="44d26-118">If state is Enabled, storageEndpoint is required.</span></span></param>
        <param name="storageAccountAccessKey"><span data-ttu-id="44d26-119">Gibt den bezeichnerschlüssel des Speicherkontos für die Bedrohungserkennung überwachen.</span><span class="sxs-lookup"><span data-stu-id="44d26-119">Specifies the identifier key of the Threat Detection audit storage account.</span></span> <span data-ttu-id="44d26-120">Wenn der Status aktiviert ist, ist die StorageAccountAccessKey erforderlich.</span><span class="sxs-lookup"><span data-stu-id="44d26-120">If state is Enabled, storageAccountAccessKey is required.</span></span></param>
        <param name="retentionDays"><span data-ttu-id="44d26-121">Gibt die Anzahl der Tage, die in den Überwachungsprotokollen für die Erkennung von Bedrohungen zu halten.</span><span class="sxs-lookup"><span data-stu-id="44d26-121">Specifies the number of days to keep in the Threat Detection audit logs.</span></span></param>
        <param name="useServerDefault"><span data-ttu-id="44d26-122">Gibt an, ob die Standardrichtlinie für Server verwenden.</span><span class="sxs-lookup"><span data-stu-id="44d26-122">Specifies whether to use the default server policy.</span></span> <span data-ttu-id="44d26-123">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="44d26-123">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="44d26-124">Initialisiert eine neue Instanz der DatabaseSecurityAlertPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="44d26-124">Initializes a new instance of the DatabaseSecurityAlertPolicy class.</span></span>
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
            <span data-ttu-id="44d26-125">Ruft ab oder legt gibt an, die durch Semikolons getrennte Liste der Warnungen, die deaktiviert sind, oder eine leere Zeichenfolge, die keine Warnungen zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="44d26-125">Gets or sets specifies the semicolon-separated list of alerts that are disabled, or empty string to disable no alerts.</span></span> <span data-ttu-id="44d26-126">Mögliche Werte: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</span><span class="sxs-lookup"><span data-stu-id="44d26-126">Possible values: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</span></span>
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
            <span data-ttu-id="44d26-127">Ruft ab oder legt gibt an, dass die Warnung für die Kontoadministratoren gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="44d26-127">Gets or sets specifies that the alert is sent to the account administrators.</span></span> <span data-ttu-id="44d26-128">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="44d26-128">Possible values include: 'Enabled', 'Disabled'</span></span>
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
            <span data-ttu-id="44d26-129">Ruft ab oder legt gibt an, die durch Semikolons getrennte Liste der e-Mail-Adressen, die an den die Warnung gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="44d26-129">Gets or sets specifies the semicolon-separated list of e-mail addresses to which the alert is sent.</span></span>
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
            <span data-ttu-id="44d26-130">Ruft die Ressourcenart ab.</span><span class="sxs-lookup"><span data-stu-id="44d26-130">Gets resource kind.</span></span>
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
            <span data-ttu-id="44d26-131">Ruft ab oder legt den geografischen Standort aktiv ist, in dem die Ressource</span><span class="sxs-lookup"><span data-stu-id="44d26-131">Gets or sets the geo-location where the resource lives</span></span>
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
            <span data-ttu-id="44d26-132">Ruft ab oder legt ihn fest gibt die Anzahl der Tage, in den Überwachungsprotokollen für die Erkennung von Bedrohungen zu halten.</span><span class="sxs-lookup"><span data-stu-id="44d26-132">Gets or sets specifies the number of days to keep in the Threat Detection audit logs.</span></span>
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
            <span data-ttu-id="44d26-133">Ruft ab oder legt gibt den Status der Richtlinie an.</span><span class="sxs-lookup"><span data-stu-id="44d26-133">Gets or sets specifies the state of the policy.</span></span> <span data-ttu-id="44d26-134">Wenn der Status aktiviert ist, sind StorageEndpoint und StorageAccountAccessKey erforderlich.</span><span class="sxs-lookup"><span data-stu-id="44d26-134">If state is Enabled, storageEndpoint and storageAccountAccessKey are required.</span></span>
            <span data-ttu-id="44d26-135">Folgende Werte sind möglich: "New", "Aktiviert", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="44d26-135">Possible values include: 'New', 'Enabled', 'Disabled'</span></span>
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
            <span data-ttu-id="44d26-136">Ruft ab oder legt ihn fest gibt den bezeichnerschlüssel des Speicherkontos für die Bedrohungserkennung Überwachung an.</span><span class="sxs-lookup"><span data-stu-id="44d26-136">Gets or sets specifies the identifier key of the Threat Detection audit storage account.</span></span> <span data-ttu-id="44d26-137">Wenn der Status aktiviert ist, ist die StorageAccountAccessKey erforderlich.</span><span class="sxs-lookup"><span data-stu-id="44d26-137">If state is Enabled, storageAccountAccessKey is required.</span></span>
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
            <span data-ttu-id="44d26-138">Ruft ab oder legt gibt der Blob-speicherendpunkt (z. B. https://MyAccount.blob.core.windows.net) an.</span><span class="sxs-lookup"><span data-stu-id="44d26-138">Gets or sets specifies the blob storage endpoint (e.g. https://MyAccount.blob.core.windows.net).</span></span> <span data-ttu-id="44d26-139">Alle Bedrohungserkennung Überwachungsprotokolle, dieses Blob-Speicher gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="44d26-139">This blob storage will hold all Threat Detection audit logs.</span></span> <span data-ttu-id="44d26-140">Wenn der Status aktiviert ist, ist die StorageEndpoint erforderlich.</span><span class="sxs-lookup"><span data-stu-id="44d26-140">If state is Enabled, storageEndpoint is required.</span></span>
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
            <span data-ttu-id="44d26-141">Gibt an, ob die Standardrichtlinie für Server verwenden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="44d26-141">Gets or sets specifies whether to use the default server policy.</span></span>
            <span data-ttu-id="44d26-142">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="44d26-142">Possible values include: 'Enabled', 'Disabled'</span></span>
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
            <span data-ttu-id="44d26-143">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="44d26-143">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="44d26-144">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="44d26-144">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>