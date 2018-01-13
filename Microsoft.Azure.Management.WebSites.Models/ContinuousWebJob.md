<Type Name="ContinuousWebJob" FullName="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob">
  <TypeSignature Language="C#" Value="public class ContinuousWebJob : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContinuousWebJob extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob" />
  <TypeSignature Language="VB.NET" Value="Public Class ContinuousWebJob&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ContinuousWebJob = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="d5530-101">Fortlaufende Web Auftragsinformationen.</span><span class="sxs-lookup"><span data-stu-id="d5530-101">Continuous Web Job Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContinuousWebJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d5530-102">Initialisiert eine neue Instanz der ContinuousWebJob-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5530-102">Initializes a new instance of the ContinuousWebJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContinuousWebJob (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt; status = null, string detailedStatus = null, string logUrl = null, string continuousWebJobName = null, string runCommand = null, string url = null, string extraInfoUrl = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; jobType = null, string error = null, Nullable&lt;bool&gt; usingSdk = null, System.Collections.Generic.IDictionary&lt;string,object&gt; settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt; status, string detailedStatus, string logUrl, string continuousWebJobName, string runCommand, string url, string extraInfoUrl, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; jobType, string error, valuetype System.Nullable`1&lt;bool&gt; usingSdk, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.#ctor(System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus},System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.WebJobType},System.String,System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional status As Nullable(Of ContinuousWebJobStatus) = null, Optional detailedStatus As String = null, Optional logUrl As String = null, Optional continuousWebJobName As String = null, Optional runCommand As String = null, Optional url As String = null, Optional extraInfoUrl As String = null, Optional jobType As Nullable(Of WebJobType) = null, Optional error As String = null, Optional usingSdk As Nullable(Of Boolean) = null, Optional settings As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob : string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt; * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob" Usage="new Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob (id, name, kind, type, status, detailedStatus, logUrl, continuousWebJobName, runCommand, url, extraInfoUrl, jobType, error, usingSdk, settings)" />
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
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt;" />
        <Parameter Name="detailedStatus" Type="System.String" />
        <Parameter Name="logUrl" Type="System.String" />
        <Parameter Name="continuousWebJobName" Type="System.String" />
        <Parameter Name="runCommand" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="extraInfoUrl" Type="System.String" />
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt;" />
        <Parameter Name="error" Type="System.String" />
        <Parameter Name="usingSdk" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d5530-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="d5530-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="d5530-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="d5530-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="d5530-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="d5530-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="d5530-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="d5530-106">Resource type.</span></span></param>
        <param name="status"><span data-ttu-id="d5530-107">Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="d5530-107">Job status.</span></span> <span data-ttu-id="d5530-108">Folgende Werte sind möglich: "Initialisierung", "Starten", "Wird ausgeführt", "PendingRestart", "angehalten"</span><span class="sxs-lookup"><span data-stu-id="d5530-108">Possible values include: 'Initializing', 'Starting', 'Running', 'PendingRestart', 'Stopped'</span></span></param>
        <param name="detailedStatus"><span data-ttu-id="d5530-109">Der ausführliche Status.</span><span class="sxs-lookup"><span data-stu-id="d5530-109">Detailed status.</span></span></param>
        <param name="logUrl"><span data-ttu-id="d5530-110">Protokoll-URL.</span><span class="sxs-lookup"><span data-stu-id="d5530-110">Log URL.</span></span></param>
        <param name="continuousWebJobName"><span data-ttu-id="d5530-111">Name des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="d5530-111">Job name.</span></span> <span data-ttu-id="d5530-112">Mit der Auftrags-ID in ARM-Ressourcen-URI verwendet.</span><span class="sxs-lookup"><span data-stu-id="d5530-112">Used as job identifier in ARM resource URI.</span></span></param>
        <param name="runCommand"><span data-ttu-id="d5530-113">Führen Sie Befehl.</span><span class="sxs-lookup"><span data-stu-id="d5530-113">Run command.</span></span></param>
        <param name="url"><span data-ttu-id="d5530-114">Projekt-URL.</span><span class="sxs-lookup"><span data-stu-id="d5530-114">Job URL.</span></span></param>
        <param name="extraInfoUrl"><span data-ttu-id="d5530-115">URL mit zusätzlichen Informationen.</span><span class="sxs-lookup"><span data-stu-id="d5530-115">Extra Info URL.</span></span></param>
        <param name="jobType"><span data-ttu-id="d5530-116">Auftragstyp.</span><span class="sxs-lookup"><span data-stu-id="d5530-116">Job type.</span></span> <span data-ttu-id="d5530-117">Folgende Werte sind möglich: "Continuous", "ausgelöst"</span><span class="sxs-lookup"><span data-stu-id="d5530-117">Possible values include: 'Continuous', 'Triggered'</span></span></param>
        <param name="error"><span data-ttu-id="d5530-118">Fehlerinformationen.</span><span class="sxs-lookup"><span data-stu-id="d5530-118">Error information.</span></span></param>
        <param name="usingSdk"><span data-ttu-id="d5530-119">Verwenden Sie die SDK?</span><span class="sxs-lookup"><span data-stu-id="d5530-119">Using SDK?</span></span></param>
        <param name="settings"><span data-ttu-id="d5530-120">Einstellungen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="d5530-120">Job settings.</span></span></param>
        <summary>
            <span data-ttu-id="d5530-121">Initialisiert eine neue Instanz der ContinuousWebJob-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5530-121">Initializes a new instance of the ContinuousWebJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuousWebJobName">
      <MemberSignature Language="C#" Value="public string ContinuousWebJobName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuousWebJobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.ContinuousWebJobName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuousWebJobName As String" />
      <MemberSignature Language="F#" Value="member this.ContinuousWebJobName : string" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.ContinuousWebJobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d5530-122">Ruft die Auftragsname ab.</span><span class="sxs-lookup"><span data-stu-id="d5530-122">Gets job name.</span></span> <span data-ttu-id="d5530-123">Mit der Auftrags-ID in ARM-Ressourcen-URI verwendet.</span><span class="sxs-lookup"><span data-stu-id="d5530-123">Used as job identifier in ARM resource URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedStatus">
      <MemberSignature Language="C#" Value="public string DetailedStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DetailedStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.DetailedStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedStatus As String" />
      <MemberSignature Language="F#" Value="member this.DetailedStatus : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.DetailedStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-124">Ruft ab, oder legt ihn fest Statusdetails.</span><span class="sxs-lookup"><span data-stu-id="d5530-124">Gets or sets detailed status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-125">Ruft ab oder legt die Fehlerinformationen.</span><span class="sxs-lookup"><span data-stu-id="d5530-125">Gets or sets error information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtraInfoUrl">
      <MemberSignature Language="C#" Value="public string ExtraInfoUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtraInfoUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.ExtraInfoUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtraInfoUrl As String" />
      <MemberSignature Language="F#" Value="member this.ExtraInfoUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.ExtraInfoUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.extraInfoUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-126">Ruft ab oder legt die URL mit zusätzlichen Informationen.</span><span class="sxs-lookup"><span data-stu-id="d5530-126">Gets or sets extra Info URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As Nullable(Of WebJobType)" />
      <MemberSignature Language="F#" Value="member this.JobType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-127">Ruft ab oder legt ihn fest Auftrag.</span><span class="sxs-lookup"><span data-stu-id="d5530-127">Gets or sets job type.</span></span> <span data-ttu-id="d5530-128">Folgende Werte sind möglich: "Continuous", "ausgelöst"</span><span class="sxs-lookup"><span data-stu-id="d5530-128">Possible values include: 'Continuous', 'Triggered'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogUrl">
      <MemberSignature Language="C#" Value="public string LogUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.LogUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property LogUrl As String" />
      <MemberSignature Language="F#" Value="member this.LogUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.LogUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.logUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-129">Abrufen oder Festlegen der Protokoll-URL.</span><span class="sxs-lookup"><span data-stu-id="d5530-129">Gets or sets log URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommand">
      <MemberSignature Language="C#" Value="public string RunCommand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunCommand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.RunCommand" />
      <MemberSignature Language="VB.NET" Value="Public Property RunCommand As String" />
      <MemberSignature Language="F#" Value="member this.RunCommand : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.RunCommand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.runCommand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-130">Ruft ab, oder legt ihn fest ausgeführten Befehls.</span><span class="sxs-lookup"><span data-stu-id="d5530-130">Gets or sets run command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property Settings As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-131">Ruft ab, oder legt ihn fest auftragseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="d5530-131">Gets or sets job settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of ContinuousWebJobStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ContinuousWebJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-132">Abrufen oder Festlegen des Auftragsstatus.</span><span class="sxs-lookup"><span data-stu-id="d5530-132">Gets or sets job status.</span></span> <span data-ttu-id="d5530-133">Folgende Werte sind möglich: "Initialisierung", "Starten", "Wird ausgeführt", "PendingRestart", "angehalten"</span><span class="sxs-lookup"><span data-stu-id="d5530-133">Possible values include: 'Initializing', 'Starting', 'Running', 'PendingRestart', 'Stopped'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-134">Abrufen oder Festlegen der URL des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="d5530-134">Gets or sets job URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsingSdk">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsingSdk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsingSdk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.UsingSdk" />
      <MemberSignature Language="VB.NET" Value="Public Property UsingSdk As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsingSdk : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ContinuousWebJob.UsingSdk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usingSdk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d5530-135">Ruft ab, oder legt sie fest, mit SDK?</span><span class="sxs-lookup"><span data-stu-id="d5530-135">Gets or sets using SDK?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>