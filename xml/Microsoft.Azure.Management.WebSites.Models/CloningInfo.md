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
            <span data-ttu-id="7e348-101">Für das Klonen Vorgang erforderlichen Informationen.</span><span class="sxs-lookup"><span data-stu-id="7e348-101">Information needed for cloning operation.</span></span>
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
            <span data-ttu-id="7e348-102">Initialisiert eine neue Instanz der CloningInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7e348-102">Initializes a new instance of the CloningInfo class.</span></span>
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
        <param name="sourceWebAppId"><span data-ttu-id="7e348-103">ARM-Ressourcen-ID der Quelle-app.</span><span class="sxs-lookup"><span data-stu-id="7e348-103">ARM resource ID of the source app.</span></span> <span data-ttu-id="7e348-104">App-Ressourcen-ID, der die Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName ist} für produktionsslots und /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} für andere Steckplätze.</span><span class="sxs-lookup"><span data-stu-id="7e348-104">App resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName} for production slots and /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} for other slots.</span></span></param>
        <param name="correlationId"><span data-ttu-id="7e348-105">Korrelations-ID des klonprozesses.</span><span class="sxs-lookup"><span data-stu-id="7e348-105">Correlation ID of cloning operation.</span></span>
            <span data-ttu-id="7e348-106">Diese ID verknüpft mehrere Klonvorgängen zusammen, um die gleichen Momentaufnahme zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="7e348-106">This ID ties multiple cloning operations together to use the same snapshot.</span></span></param>
        <param name="overwrite"><span data-ttu-id="7e348-107">&lt;Code&gt;"true"&lt;/code&gt; zum Überschreiben der Ziel-app; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-107">&lt;code&gt;true&lt;/code&gt; to overwrite destination app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="cloneCustomHostNames"><span data-ttu-id="7e348-108">&lt;Code&gt;"true"&lt;/code&gt; benutzerdefinierte Hostnamen aus Quelle-app zu klonen, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-108">&lt;code&gt;true&lt;/code&gt; to clone custom hostnames from source app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="cloneSourceControl"><span data-ttu-id="7e348-109">&lt;Code&gt;"true"&lt;/code&gt; Datenquellen-Steuerelement aus der Quelle-app zu klonen, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-109">&lt;code&gt;true&lt;/code&gt; to clone source control from source app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hostingEnvironment"><span data-ttu-id="7e348-110">App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="7e348-110">App Service Environment.</span></span></param>
        <param name="appSettingsOverrides"><span data-ttu-id="7e348-111">Anwendung Festlegen von Außerkraftsetzungen für die geklonte app.</span><span class="sxs-lookup"><span data-stu-id="7e348-111">Application setting overrides for cloned app.</span></span> <span data-ttu-id="7e348-112">Diese Einstellungen überschreiben, wenn angegeben, die Einstellungen aus der Quelle-app geklont.</span><span class="sxs-lookup"><span data-stu-id="7e348-112">If specified, these settings override the settings cloned from source app.</span></span> <span data-ttu-id="7e348-113">Andernfalls werden die Anwendungseinstellungen von Quell-app beibehalten.</span><span class="sxs-lookup"><span data-stu-id="7e348-113">Otherwise, application settings from source app are retained.</span></span></param>
        <param name="configureLoadBalancing"><span data-ttu-id="7e348-114">&lt;Code&gt;"true"&lt;/code&gt; so konfigurieren Sie einen Lastenausgleich für die Quelle und Ziel-app.</span><span class="sxs-lookup"><span data-stu-id="7e348-114">&lt;code&gt;true&lt;/code&gt; to configure load balancing for source and destination app.</span></span></param>
        <param name="trafficManagerProfileId"><span data-ttu-id="7e348-115">ARM Ressourcen-ID der Traffic Manager-Profil zu verwenden, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7e348-115">ARM resource ID of the Traffic Manager profile to use, if it exists.</span></span> <span data-ttu-id="7e348-116">Traffic Manager-Ressourcen-ID wird von der Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</span><span class="sxs-lookup"><span data-stu-id="7e348-116">Traffic Manager resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</span></span></param>
        <param name="trafficManagerProfileName"><span data-ttu-id="7e348-117">Name des Traffic Manager-Profil zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7e348-117">Name of Traffic Manager profile to create.</span></span> <span data-ttu-id="7e348-118">Dies ist nur erforderlich, wenn Traffic Manager-Profil nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7e348-118">This is only needed if Traffic Manager profile does not already exist.</span></span></param>
        <param name="ignoreQuotas"><span data-ttu-id="7e348-119">&lt;Code&gt;"true"&lt;/code&gt; Wenn Kontingente ignoriert, andernfalls werden soll &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-119">&lt;code&gt;true&lt;/code&gt; if quotas should be ignored; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <summary>
            <span data-ttu-id="7e348-120">Initialisiert eine neue Instanz der CloningInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7e348-120">Initializes a new instance of the CloningInfo class.</span></span>
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
            <span data-ttu-id="7e348-121">Abrufen oder Festlegen der Anwendung Festlegen von Außerkraftsetzungen für die geklonte-app.</span><span class="sxs-lookup"><span data-stu-id="7e348-121">Gets or sets application setting overrides for cloned app.</span></span> <span data-ttu-id="7e348-122">Diese Einstellungen überschreiben, wenn angegeben, die Einstellungen aus der Quelle-app geklont.</span><span class="sxs-lookup"><span data-stu-id="7e348-122">If specified, these settings override the settings cloned from source app.</span></span> <span data-ttu-id="7e348-123">Andernfalls werden die Anwendungseinstellungen von Quell-app beibehalten.</span><span class="sxs-lookup"><span data-stu-id="7e348-123">Otherwise, application settings from source app are retained.</span></span>
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
            <span data-ttu-id="7e348-124">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; benutzerdefinierte Hostnamen aus Quelle-app zu klonen, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp; Gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-124">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to clone custom hostnames from source app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
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
            <span data-ttu-id="7e348-125">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Datenquellen-Steuerelement aus der Quelle-app zu klonen, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt ;.</span><span class="sxs-lookup"><span data-stu-id="7e348-125">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to clone source control from source app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
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
            <span data-ttu-id="7e348-126">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So konfigurieren Sie einen Lastenausgleich für die Quelle und Ziel-app.</span><span class="sxs-lookup"><span data-stu-id="7e348-126">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to configure load balancing for source and destination app.</span></span>
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
            <span data-ttu-id="7e348-127">Ruft ab, oder legt ihn fest Korrelations-ID des klonprozesses.</span><span class="sxs-lookup"><span data-stu-id="7e348-127">Gets or sets correlation ID of cloning operation.</span></span> <span data-ttu-id="7e348-128">Diese ID verknüpft mehrere Klonvorgängen zusammen, um die gleichen Momentaufnahme zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="7e348-128">This ID ties multiple cloning operations together to use the same snapshot.</span></span>
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
            <span data-ttu-id="7e348-129">Ruft ab oder legt die app Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="7e348-129">Gets or sets app Service Environment.</span></span>
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
            <span data-ttu-id="7e348-130">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Kontingente ignoriert, andernfalls werden soll &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-130">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if quotas should be ignored; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
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
            <span data-ttu-id="7e348-131">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Ziel-app; überschreiben, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="7e348-131">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to overwrite destination app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
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
            <span data-ttu-id="7e348-132">Ruft ab, oder legt ihn fest ARM-Ressourcen-ID der Quelle-app.</span><span class="sxs-lookup"><span data-stu-id="7e348-132">Gets or sets ARM resource ID of the source app.</span></span> <span data-ttu-id="7e348-133">App-Ressourcen-ID, der die Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName ist} für produktionsslots und /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} für andere Steckplätze.</span><span class="sxs-lookup"><span data-stu-id="7e348-133">App resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName} for production slots and /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} for other slots.</span></span>
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
            <span data-ttu-id="7e348-134">Ruft ab oder legt ARM-Ressourcen-ID der Traffic Manager-Profil zu verwenden, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7e348-134">Gets or sets ARM resource ID of the Traffic Manager profile to use, if it exists.</span></span> <span data-ttu-id="7e348-135">Traffic Manager-Ressourcen-ID wird von der Form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</span><span class="sxs-lookup"><span data-stu-id="7e348-135">Traffic Manager resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</span></span>
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
            <span data-ttu-id="7e348-136">Ruft ab, oder legt ihn fest Name des Traffic Manager-Profil zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7e348-136">Gets or sets name of Traffic Manager profile to create.</span></span> <span data-ttu-id="7e348-137">Dies ist nur erforderlich, wenn Traffic Manager-Profil nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7e348-137">This is only needed if Traffic Manager profile does not already exist.</span></span>
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
            <span data-ttu-id="7e348-138">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7e348-138">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7e348-139">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7e348-139">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>