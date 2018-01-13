<Type Name="TriggeredWebJob" FullName="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob">
  <TypeSignature Language="C#" Value="public class TriggeredWebJob : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggeredWebJob extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggeredWebJob&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type TriggeredWebJob = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="0d592-101">Web-Auftragsinformationen wird ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="0d592-101">Triggered Web Job Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggeredWebJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d592-102">Initialisiert eine neue Instanz der TriggeredWebJob-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0d592-102">Initializes a new instance of the TriggeredWebJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggeredWebJob (string id = null, string name = null, string kind = null, string type = null, Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun latestRun = null, string historyUrl = null, string schedulerLogsUrl = null, string triggeredWebJobName = null, string runCommand = null, string url = null, string extraInfoUrl = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; jobType = null, string error = null, Nullable&lt;bool&gt; usingSdk = null, System.Collections.Generic.IDictionary&lt;string,object&gt; settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun latestRun, string historyUrl, string schedulerLogsUrl, string triggeredWebJobName, string runCommand, string url, string extraInfoUrl, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; jobType, string error, valuetype System.Nullable`1&lt;bool&gt; usingSdk, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.WebJobType},System.String,System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional latestRun As TriggeredJobRun = null, Optional historyUrl As String = null, Optional schedulerLogsUrl As String = null, Optional triggeredWebJobName As String = null, Optional runCommand As String = null, Optional url As String = null, Optional extraInfoUrl As String = null, Optional jobType As Nullable(Of WebJobType) = null, Optional error As String = null, Optional usingSdk As Nullable(Of Boolean) = null, Optional settings As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob : string * string * string * string * Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob" Usage="new Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob (id, name, kind, type, latestRun, historyUrl, schedulerLogsUrl, triggeredWebJobName, runCommand, url, extraInfoUrl, jobType, error, usingSdk, settings)" />
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
        <Parameter Name="latestRun" Type="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun" />
        <Parameter Name="historyUrl" Type="System.String" />
        <Parameter Name="schedulerLogsUrl" Type="System.String" />
        <Parameter Name="triggeredWebJobName" Type="System.String" />
        <Parameter Name="runCommand" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="extraInfoUrl" Type="System.String" />
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt;" />
        <Parameter Name="error" Type="System.String" />
        <Parameter Name="usingSdk" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="0d592-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="0d592-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="0d592-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="0d592-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="0d592-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="0d592-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="0d592-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="0d592-106">Resource type.</span></span></param>
        <param name="latestRun"><span data-ttu-id="0d592-107">Neuester Auftrag Informationen führen.</span><span class="sxs-lookup"><span data-stu-id="0d592-107">Latest job run information.</span></span></param>
        <param name="historyUrl"><span data-ttu-id="0d592-108">Verlauf-URL.</span><span class="sxs-lookup"><span data-stu-id="0d592-108">History URL.</span></span></param>
        <param name="schedulerLogsUrl"><span data-ttu-id="0d592-109">URL für Scheduler-Protokolle.</span><span class="sxs-lookup"><span data-stu-id="0d592-109">Scheduler Logs URL.</span></span></param>
        <param name="triggeredWebJobName"><span data-ttu-id="0d592-110">Name des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="0d592-110">Job name.</span></span> <span data-ttu-id="0d592-111">Mit der Auftrags-ID in ARM-Ressourcen-URI verwendet.</span><span class="sxs-lookup"><span data-stu-id="0d592-111">Used as job identifier in ARM resource URI.</span></span></param>
        <param name="runCommand"><span data-ttu-id="0d592-112">Führen Sie Befehl.</span><span class="sxs-lookup"><span data-stu-id="0d592-112">Run command.</span></span></param>
        <param name="url"><span data-ttu-id="0d592-113">Projekt-URL.</span><span class="sxs-lookup"><span data-stu-id="0d592-113">Job URL.</span></span></param>
        <param name="extraInfoUrl"><span data-ttu-id="0d592-114">URL mit zusätzlichen Informationen.</span><span class="sxs-lookup"><span data-stu-id="0d592-114">Extra Info URL.</span></span></param>
        <param name="jobType"><span data-ttu-id="0d592-115">Auftragstyp.</span><span class="sxs-lookup"><span data-stu-id="0d592-115">Job type.</span></span> <span data-ttu-id="0d592-116">Folgende Werte sind möglich: "Continuous", "ausgelöst"</span><span class="sxs-lookup"><span data-stu-id="0d592-116">Possible values include: 'Continuous', 'Triggered'</span></span></param>
        <param name="error"><span data-ttu-id="0d592-117">Fehlerinformationen.</span><span class="sxs-lookup"><span data-stu-id="0d592-117">Error information.</span></span></param>
        <param name="usingSdk"><span data-ttu-id="0d592-118">Verwenden Sie die SDK?</span><span class="sxs-lookup"><span data-stu-id="0d592-118">Using SDK?</span></span></param>
        <param name="settings"><span data-ttu-id="0d592-119">Einstellungen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0d592-119">Job settings.</span></span></param>
        <summary>
            <span data-ttu-id="0d592-120">Initialisiert eine neue Instanz der TriggeredWebJob-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0d592-120">Initializes a new instance of the TriggeredWebJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.Error" />
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
            <span data-ttu-id="0d592-121">Ruft ab oder legt die Fehlerinformationen.</span><span class="sxs-lookup"><span data-stu-id="0d592-121">Gets or sets error information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtraInfoUrl">
      <MemberSignature Language="C#" Value="public string ExtraInfoUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtraInfoUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.ExtraInfoUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtraInfoUrl As String" />
      <MemberSignature Language="F#" Value="member this.ExtraInfoUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.ExtraInfoUrl" />
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
            <span data-ttu-id="0d592-122">Ruft ab oder legt die URL mit zusätzlichen Informationen.</span><span class="sxs-lookup"><span data-stu-id="0d592-122">Gets or sets extra Info URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HistoryUrl">
      <MemberSignature Language="C#" Value="public string HistoryUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HistoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.HistoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property HistoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.HistoryUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.HistoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.historyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d592-123">Ruft ab, oder legt ihn fest Verlauf URL.</span><span class="sxs-lookup"><span data-stu-id="0d592-123">Gets or sets history URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As Nullable(Of WebJobType)" />
      <MemberSignature Language="F#" Value="member this.JobType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.JobType" />
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
            <span data-ttu-id="0d592-124">Ruft ab oder legt ihn fest Auftrag.</span><span class="sxs-lookup"><span data-stu-id="0d592-124">Gets or sets job type.</span></span> <span data-ttu-id="0d592-125">Folgende Werte sind möglich: "Continuous", "ausgelöst"</span><span class="sxs-lookup"><span data-stu-id="0d592-125">Possible values include: 'Continuous', 'Triggered'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LatestRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun LatestRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun LatestRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.LatestRun" />
      <MemberSignature Language="VB.NET" Value="Public Property LatestRun As TriggeredJobRun" />
      <MemberSignature Language="F#" Value="member this.LatestRun : Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.LatestRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.latestRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d592-126">Ruft ab, oder legt ihn fest neuesten Auftrag Informationen führen.</span><span class="sxs-lookup"><span data-stu-id="0d592-126">Gets or sets latest job run information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommand">
      <MemberSignature Language="C#" Value="public string RunCommand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunCommand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.RunCommand" />
      <MemberSignature Language="VB.NET" Value="Public Property RunCommand As String" />
      <MemberSignature Language="F#" Value="member this.RunCommand : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.RunCommand" />
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
            <span data-ttu-id="0d592-127">Ruft ab, oder legt ihn fest ausgeführten Befehls.</span><span class="sxs-lookup"><span data-stu-id="0d592-127">Gets or sets run command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulerLogsUrl">
      <MemberSignature Language="C#" Value="public string SchedulerLogsUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchedulerLogsUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.SchedulerLogsUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulerLogsUrl As String" />
      <MemberSignature Language="F#" Value="member this.SchedulerLogsUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.SchedulerLogsUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schedulerLogsUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d592-128">Ruft ab, oder legt ihn fest Scheduler URL-Protokolle.</span><span class="sxs-lookup"><span data-stu-id="0d592-128">Gets or sets scheduler Logs URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property Settings As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.Settings" />
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
            <span data-ttu-id="0d592-129">Ruft ab, oder legt ihn fest auftragseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="0d592-129">Gets or sets job settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggeredWebJobName">
      <MemberSignature Language="C#" Value="public string TriggeredWebJobName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggeredWebJobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.TriggeredWebJobName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggeredWebJobName As String" />
      <MemberSignature Language="F#" Value="member this.TriggeredWebJobName : string" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.TriggeredWebJobName" />
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
            <span data-ttu-id="0d592-130">Ruft die Auftragsname ab.</span><span class="sxs-lookup"><span data-stu-id="0d592-130">Gets job name.</span></span> <span data-ttu-id="0d592-131">Mit der Auftrags-ID in ARM-Ressourcen-URI verwendet.</span><span class="sxs-lookup"><span data-stu-id="0d592-131">Used as job identifier in ARM resource URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.Url" />
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
            <span data-ttu-id="0d592-132">Abrufen oder Festlegen der URL des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="0d592-132">Gets or sets job URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsingSdk">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsingSdk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsingSdk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.UsingSdk" />
      <MemberSignature Language="VB.NET" Value="Public Property UsingSdk As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsingSdk : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredWebJob.UsingSdk" />
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
            <span data-ttu-id="0d592-133">Ruft ab, oder legt sie fest, mit SDK?</span><span class="sxs-lookup"><span data-stu-id="0d592-133">Gets or sets using SDK?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>