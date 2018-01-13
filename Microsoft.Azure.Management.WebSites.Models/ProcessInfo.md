<Type Name="ProcessInfo" FullName="Microsoft.Azure.Management.WebSites.Models.ProcessInfo">
  <TypeSignature Language="C#" Value="public class ProcessInfo : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProcessInfo extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ProcessInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ProcessInfo&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ProcessInfo = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="3c6b3-101">Prozess-Informationen.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-101">Process Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProcessInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-102">Initialisiert eine neue Instanz der Klasse ProcessInfo an.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-102">Initializes a new instance of the ProcessInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProcessInfo (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; processInfoId = null, string processInfoName = null, string href = null, string miniDump = null, Nullable&lt;bool&gt; isProfileRunning = null, Nullable&lt;bool&gt; isIisProfileRunning = null, Nullable&lt;double&gt; iisProfileTimeoutInSeconds = null, string parent = null, System.Collections.Generic.IList&lt;string&gt; children = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt; threads = null, System.Collections.Generic.IList&lt;string&gt; openFileHandles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt; modules = null, string fileName = null, string commandLine = null, string userName = null, Nullable&lt;int&gt; handleCount = null, Nullable&lt;int&gt; moduleCount = null, Nullable&lt;int&gt; threadCount = null, Nullable&lt;DateTime&gt; startTime = null, string totalProcessorTime = null, string userProcessorTime = null, string privilegedProcessorTime = null, Nullable&lt;long&gt; workingSet64 = null, Nullable&lt;long&gt; peakWorkingSet64 = null, Nullable&lt;long&gt; privateMemorySize64 = null, Nullable&lt;long&gt; virtualMemorySize64 = null, Nullable&lt;long&gt; peakVirtualMemorySize64 = null, Nullable&lt;long&gt; pagedSystemMemorySize64 = null, Nullable&lt;long&gt; nonpagedSystemMemorySize64 = null, Nullable&lt;long&gt; pagedMemorySize64 = null, Nullable&lt;long&gt; peakPagedMemorySize64 = null, Nullable&lt;DateTime&gt; timeStamp = null, System.Collections.Generic.IDictionary&lt;string,string&gt; environmentVariables = null, Nullable&lt;bool&gt; isScmSite = null, Nullable&lt;bool&gt; isWebJob = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; processInfoId, string processInfoName, string href, string miniDump, valuetype System.Nullable`1&lt;bool&gt; isProfileRunning, valuetype System.Nullable`1&lt;bool&gt; isIisProfileRunning, valuetype System.Nullable`1&lt;float64&gt; iisProfileTimeoutInSeconds, string parent, class System.Collections.Generic.IList`1&lt;string&gt; children, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt; threads, class System.Collections.Generic.IList`1&lt;string&gt; openFileHandles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt; modules, string fileName, string commandLine, string userName, valuetype System.Nullable`1&lt;int32&gt; handleCount, valuetype System.Nullable`1&lt;int32&gt; moduleCount, valuetype System.Nullable`1&lt;int32&gt; threadCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string totalProcessorTime, string userProcessorTime, string privilegedProcessorTime, valuetype System.Nullable`1&lt;int64&gt; workingSet64, valuetype System.Nullable`1&lt;int64&gt; peakWorkingSet64, valuetype System.Nullable`1&lt;int64&gt; privateMemorySize64, valuetype System.Nullable`1&lt;int64&gt; virtualMemorySize64, valuetype System.Nullable`1&lt;int64&gt; peakVirtualMemorySize64, valuetype System.Nullable`1&lt;int64&gt; pagedSystemMemorySize64, valuetype System.Nullable`1&lt;int64&gt; nonpagedSystemMemorySize64, valuetype System.Nullable`1&lt;int64&gt; pagedMemorySize64, valuetype System.Nullable`1&lt;int64&gt; peakPagedMemorySize64, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeStamp, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; environmentVariables, valuetype System.Nullable`1&lt;bool&gt; isScmSite, valuetype System.Nullable`1&lt;bool&gt; isWebJob, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Double},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.DateTime},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional processInfoId As Nullable(Of Integer) = null, Optional processInfoName As String = null, Optional href As String = null, Optional miniDump As String = null, Optional isProfileRunning As Nullable(Of Boolean) = null, Optional isIisProfileRunning As Nullable(Of Boolean) = null, Optional iisProfileTimeoutInSeconds As Nullable(Of Double) = null, Optional parent As String = null, Optional children As IList(Of String) = null, Optional threads As IList(Of ProcessThreadInfo) = null, Optional openFileHandles As IList(Of String) = null, Optional modules As IList(Of ProcessModuleInfo) = null, Optional fileName As String = null, Optional commandLine As String = null, Optional userName As String = null, Optional handleCount As Nullable(Of Integer) = null, Optional moduleCount As Nullable(Of Integer) = null, Optional threadCount As Nullable(Of Integer) = null, Optional startTime As Nullable(Of DateTime) = null, Optional totalProcessorTime As String = null, Optional userProcessorTime As String = null, Optional privilegedProcessorTime As String = null, Optional workingSet64 As Nullable(Of Long) = null, Optional peakWorkingSet64 As Nullable(Of Long) = null, Optional privateMemorySize64 As Nullable(Of Long) = null, Optional virtualMemorySize64 As Nullable(Of Long) = null, Optional peakVirtualMemorySize64 As Nullable(Of Long) = null, Optional pagedSystemMemorySize64 As Nullable(Of Long) = null, Optional nonpagedSystemMemorySize64 As Nullable(Of Long) = null, Optional pagedMemorySize64 As Nullable(Of Long) = null, Optional peakPagedMemorySize64 As Nullable(Of Long) = null, Optional timeStamp As Nullable(Of DateTime) = null, Optional environmentVariables As IDictionary(Of String, String) = null, Optional isScmSite As Nullable(Of Boolean) = null, Optional isWebJob As Nullable(Of Boolean) = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ProcessInfo : string * string * string * string * Nullable&lt;int&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;double&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.ProcessInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.ProcessInfo (id, name, kind, type, processInfoId, processInfoName, href, miniDump, isProfileRunning, isIisProfileRunning, iisProfileTimeoutInSeconds, parent, children, threads, openFileHandles, modules, fileName, commandLine, userName, handleCount, moduleCount, threadCount, startTime, totalProcessorTime, userProcessorTime, privilegedProcessorTime, workingSet64, peakWorkingSet64, privateMemorySize64, virtualMemorySize64, peakVirtualMemorySize64, pagedSystemMemorySize64, nonpagedSystemMemorySize64, pagedMemorySize64, peakPagedMemorySize64, timeStamp, environmentVariables, isScmSite, isWebJob, description)" />
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
        <Parameter Name="processInfoId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="processInfoName" Type="System.String" />
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="miniDump" Type="System.String" />
        <Parameter Name="isProfileRunning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isIisProfileRunning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="iisProfileTimeoutInSeconds" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="parent" Type="System.String" />
        <Parameter Name="children" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="threads" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt;" />
        <Parameter Name="openFileHandles" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="modules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt;" />
        <Parameter Name="fileName" Type="System.String" />
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="handleCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="moduleCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="threadCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="totalProcessorTime" Type="System.String" />
        <Parameter Name="userProcessorTime" Type="System.String" />
        <Parameter Name="privilegedProcessorTime" Type="System.String" />
        <Parameter Name="workingSet64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="peakWorkingSet64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="privateMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="virtualMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="peakVirtualMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="pagedSystemMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="nonpagedSystemMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="pagedMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="peakPagedMemorySize64" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="timeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="isScmSite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isWebJob" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3c6b3-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="3c6b3-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="3c6b3-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="3c6b3-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-106">Resource type.</span></span></param>
        <param name="processInfoId"><span data-ttu-id="3c6b3-107">ARM-Bezeichner für die Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-107">ARM Identifier for deployment.</span></span></param>
        <param name="processInfoName"><span data-ttu-id="3c6b3-108">Bereitstellungsname.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-108">Deployment name.</span></span></param>
        <param name="href"><span data-ttu-id="3c6b3-109">HRef-URI.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-109">HRef URI.</span></span></param>
        <param name="miniDump"><span data-ttu-id="3c6b3-110">Minidump-URI.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-110">Minidump URI.</span></span></param>
        <param name="isProfileRunning"><span data-ttu-id="3c6b3-111">Werden Profil wird ausgeführt?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-111">Is profile running?</span></span></param>
        <param name="isIisProfileRunning"><span data-ttu-id="3c6b3-112">Werden das IIS-Profil wird ausgeführt?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-112">Is the IIS Profile running?</span></span></param>
        <param name="iisProfileTimeoutInSeconds"><span data-ttu-id="3c6b3-113">Profil für die IIS-Timeout (Sekunden).</span><span class="sxs-lookup"><span data-stu-id="3c6b3-113">IIS Profile timeout (seconds).</span></span></param>
        <param name="parent"><span data-ttu-id="3c6b3-114">Übergeordnete Prozess.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-114">Parent process.</span></span></param>
        <param name="children"><span data-ttu-id="3c6b3-115">Liste der untergeordneten Prozess.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-115">Child process list.</span></span></param>
        <param name="threads"><span data-ttu-id="3c6b3-116">Threadliste.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-116">Thread list.</span></span></param>
        <param name="openFileHandles"><span data-ttu-id="3c6b3-117">Liste der geöffneten Dateien.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-117">List of open files.</span></span></param>
        <param name="modules"><span data-ttu-id="3c6b3-118">Die Liste der Module.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-118">List of modules.</span></span></param>
        <param name="fileName"><span data-ttu-id="3c6b3-119">Der Dateiname dieses Prozesses.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-119">File name of this process.</span></span></param>
        <param name="commandLine"><span data-ttu-id="3c6b3-120">Über die Befehlszeile.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-120">Command line.</span></span></param>
        <param name="userName"><span data-ttu-id="3c6b3-121">Benutzername.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-121">User name.</span></span></param>
        <param name="handleCount"><span data-ttu-id="3c6b3-122">Anzahl der Handles.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-122">Handle count.</span></span></param>
        <param name="moduleCount"><span data-ttu-id="3c6b3-123">Anzahl der Module.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-123">Module count.</span></span></param>
        <param name="threadCount"><span data-ttu-id="3c6b3-124">Anzahl der Threads.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-124">Thread count.</span></span></param>
        <param name="startTime"><span data-ttu-id="3c6b3-125">Die Startzeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-125">Start time.</span></span></param>
        <param name="totalProcessorTime"><span data-ttu-id="3c6b3-126">Gesamte CPU-Zeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-126">Total CPU time.</span></span></param>
        <param name="userProcessorTime"><span data-ttu-id="3c6b3-127">Benutzer-CPU-Zeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-127">User CPU time.</span></span></param>
        <param name="privilegedProcessorTime"><span data-ttu-id="3c6b3-128">Privilegierte CPU-Zeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-128">Privileged CPU time.</span></span></param>
        <param name="workingSet64"><span data-ttu-id="3c6b3-129">Workingset.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-129">Working set.</span></span></param>
        <param name="peakWorkingSet64"><span data-ttu-id="3c6b3-130">Peak Workingsets.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-130">Peak working set.</span></span></param>
        <param name="privateMemorySize64"><span data-ttu-id="3c6b3-131">Größe des privaten Speichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-131">Private memory size.</span></span></param>
        <param name="virtualMemorySize64"><span data-ttu-id="3c6b3-132">Die Größe des virtuellen Speichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-132">Virtual memory size.</span></span></param>
        <param name="peakVirtualMemorySize64"><span data-ttu-id="3c6b3-133">Maximale Auslastung des virtuellen Speichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-133">Peak virtual memory usage.</span></span></param>
        <param name="pagedSystemMemorySize64"><span data-ttu-id="3c6b3-134">Ausgelagerten Systemspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-134">Paged system memory.</span></span></param>
        <param name="nonpagedSystemMemorySize64"><span data-ttu-id="3c6b3-135">Nicht ausgelagerten Systemspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-135">Non-paged system memory.</span></span></param>
        <param name="pagedMemorySize64"><span data-ttu-id="3c6b3-136">Ausgelagerte Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-136">Paged memory.</span></span></param>
        <param name="peakPagedMemorySize64"><span data-ttu-id="3c6b3-137">Die maximale ausgelagerten Arbeitsspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-137">Peak paged memory.</span></span></param>
        <param name="timeStamp"><span data-ttu-id="3c6b3-138">Zeitstempel.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-138">Time stamp.</span></span></param>
        <param name="environmentVariables"><span data-ttu-id="3c6b3-139">Liste von Umgebungsvariablen.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-139">List of environment variables.</span></span></param>
        <param name="isScmSite"><span data-ttu-id="3c6b3-140">Handelt es sich um den SCM Standort?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-140">Is this the SCM site?</span></span></param>
        <param name="isWebJob"><span data-ttu-id="3c6b3-141">Handelt es sich um einen Webauftrag?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-141">Is this a Web Job?</span></span></param>
        <param name="description"><span data-ttu-id="3c6b3-142">Beschreibung des Prozesses.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-142">Description of process.</span></span></param>
        <summary>
            <span data-ttu-id="3c6b3-143">Initialisiert eine neue Instanz der Klasse ProcessInfo an.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-143">Initializes a new instance of the ProcessInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Children">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Children { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Children" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Children" />
      <MemberSignature Language="VB.NET" Value="Public Property Children As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Children : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Children" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.children")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-144">Abrufen oder Festlegen der Liste der untergeordneten Prozess.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-144">Gets or sets child process list.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-145">Ruft ab, oder legt die Befehlszeile fest.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-145">Gets or sets command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Description" />
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
            <span data-ttu-id="3c6b3-146">Ruft ab oder legt die Beschreibung des Prozesses.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-146">Gets or sets description of process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.EnvironmentVariables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentVariables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-147">Ruft ab oder legt die Liste von Umgebungsvariablen.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-147">Gets or sets list of environment variables.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public string FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As String" />
      <MemberSignature Language="F#" Value="member this.FileName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.FileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fileName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-148">Ruft ab oder legt den Namen dieses Vorgangs fest.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-148">Gets or sets file name of this process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; HandleCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; HandleCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.HandleCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HandleCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.HandleCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.HandleCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.handleCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-149">Ruft ab oder legt die maximale Handleanzahl beträgt.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-149">Gets or sets handle count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Href">
      <MemberSignature Language="C#" Value="public string Href { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Href" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Href" />
      <MemberSignature Language="VB.NET" Value="Public Property Href As String" />
      <MemberSignature Language="F#" Value="member this.Href : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Href" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.href")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-150">Ruft ab, oder legt ihn fest hRef URI.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-150">Gets or sets hRef URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IisProfileTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; IisProfileTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; IisProfileTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IisProfileTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IisProfileTimeoutInSeconds As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.IisProfileTimeoutInSeconds : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IisProfileTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.iisProfileTimeoutInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-151">Abrufen oder Festlegen der IIS-Profil-Timeout (Sekunden).</span><span class="sxs-lookup"><span data-stu-id="3c6b3-151">Gets or sets IIS Profile timeout (seconds).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIisProfileRunning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsIisProfileRunning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsIisProfileRunning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsIisProfileRunning" />
      <MemberSignature Language="VB.NET" Value="Public Property IsIisProfileRunning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsIisProfileRunning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsIisProfileRunning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isIisProfileRunning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-152">Ruft ab oder legt ihn fest ist das IIS-Profil ausgeführt?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-152">Gets or sets is the IIS Profile running?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsProfileRunning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsProfileRunning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsProfileRunning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsProfileRunning" />
      <MemberSignature Language="VB.NET" Value="Public Property IsProfileRunning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsProfileRunning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsProfileRunning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isProfileRunning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-153">Ruft ab oder legt ihn fest ist Profil ausgeführt?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-153">Gets or sets is profile running?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsScmSite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsScmSite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsScmSite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsScmSite" />
      <MemberSignature Language="VB.NET" Value="Public Property IsScmSite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsScmSite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsScmSite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isScmSite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-154">Ruft ab oder legt ihn fest ist dies der SCM-Standort?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-154">Gets or sets is this the SCM site?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWebJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsWebJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsWebJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsWebJob" />
      <MemberSignature Language="VB.NET" Value="Public Property IsWebJob As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsWebJob : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.IsWebJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isWebJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-155">Ruft ab oder legt ihn fest ist dies einen Webauftrag?</span><span class="sxs-lookup"><span data-stu-id="3c6b3-155">Gets or sets is this a Web Job?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MiniDump">
      <MemberSignature Language="C#" Value="public string MiniDump { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MiniDump" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.MiniDump" />
      <MemberSignature Language="VB.NET" Value="Public Property MiniDump As String" />
      <MemberSignature Language="F#" Value="member this.MiniDump : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.MiniDump" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.miniDump")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-156">Ruft ab, oder legt ihn fest Minidump URI.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-156">Gets or sets minidump URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModuleCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ModuleCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ModuleCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ModuleCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ModuleCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ModuleCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ModuleCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.moduleCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-157">Ruft ab, oder legt ihn fest Modulanzahl.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-157">Gets or sets module count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Modules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt; Modules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt; Modules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Modules" />
      <MemberSignature Language="VB.NET" Value="Public Property Modules As IList(Of ProcessModuleInfo)" />
      <MemberSignature Language="F#" Value="member this.Modules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Modules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.modules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessModuleInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-158">Ruft ab oder legt die Liste der Module fest.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-158">Gets or sets list of modules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NonpagedSystemMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; NonpagedSystemMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; NonpagedSystemMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.NonpagedSystemMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property NonpagedSystemMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.NonpagedSystemMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.NonpagedSystemMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nonpagedSystemMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-159">Ruft ab oder legt des nicht ausgelagerten Systemspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-159">Gets or sets non-paged system memory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenFileHandles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OpenFileHandles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OpenFileHandles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.OpenFileHandles" />
      <MemberSignature Language="VB.NET" Value="Public Property OpenFileHandles As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OpenFileHandles : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.OpenFileHandles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.openFileHandles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-160">Ruft ab oder legt die Liste der geöffneten Dateien.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-160">Gets or sets list of open files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PagedMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PagedMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PagedMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PagedMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property PagedMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PagedMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PagedMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pagedMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-161">Ruft ab, oder legt ihn fest Auslagerungsspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-161">Gets or sets paged memory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PagedSystemMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PagedSystemMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PagedSystemMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PagedSystemMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property PagedSystemMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PagedSystemMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PagedSystemMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pagedSystemMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-162">Ruft ab, oder legt ihn fest ausgelagerten Systemspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-162">Gets or sets paged system memory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public string Parent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Parent" />
      <MemberSignature Language="VB.NET" Value="Public Property Parent As String" />
      <MemberSignature Language="F#" Value="member this.Parent : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.parent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-163">Ruft ab, oder legt ihn fest übergeordneten Prozess.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-163">Gets or sets parent process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakPagedMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PeakPagedMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PeakPagedMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PeakPagedMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakPagedMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PeakPagedMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PeakPagedMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peakPagedMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-164">Ruft ab, oder legt ihn fest Spitzenzeiten des ausgelagerten Arbeitsspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-164">Gets or sets peak paged memory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakVirtualMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PeakVirtualMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PeakVirtualMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PeakVirtualMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakVirtualMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PeakVirtualMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PeakVirtualMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peakVirtualMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-165">Ruft ab, oder legt ihn fest spitzenauslastung des virtuellen Arbeitsspeichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-165">Gets or sets peak virtual memory usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakWorkingSet64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PeakWorkingSet64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PeakWorkingSet64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PeakWorkingSet64" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakWorkingSet64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PeakWorkingSet64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PeakWorkingSet64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peakWorkingSet64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-166">Ruft ab, oder legt ihn fest Peak Workingsets.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-166">Gets or sets peak working set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrivateMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrivateMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PrivateMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrivateMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PrivateMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-167">Ruft ab oder legt die Größe des privaten Speichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-167">Gets or sets private memory size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivilegedProcessorTime">
      <MemberSignature Language="C#" Value="public string PrivilegedProcessorTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivilegedProcessorTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PrivilegedProcessorTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivilegedProcessorTime As String" />
      <MemberSignature Language="F#" Value="member this.PrivilegedProcessorTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.PrivilegedProcessorTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privilegedProcessorTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-168">Ruft ab, oder legt ihn fest privilegierte CPU-Zeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-168">Gets or sets privileged CPU time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessInfoId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessInfoId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessInfoId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ProcessInfoId" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessInfoId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessInfoId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ProcessInfoId" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-169">Ruft ab oder legt ARM-Bezeichner für die Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-169">Gets or sets ARM Identifier for deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessInfoName">
      <MemberSignature Language="C#" Value="public string ProcessInfoName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProcessInfoName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ProcessInfoName" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessInfoName As String" />
      <MemberSignature Language="F#" Value="member this.ProcessInfoName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ProcessInfoName" />
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
            <span data-ttu-id="3c6b3-170">Ruft ab, oder legt ihn fest Bereitstellungsname.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-170">Gets or sets deployment name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-171">Ruft ab oder legt die Startzeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-171">Gets or sets start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThreadCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ThreadCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ThreadCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ThreadCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.ThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.threadCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-172">Ruft ab oder legt die Anzahl der Threads fest.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-172">Gets or sets thread count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Threads">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt; Threads { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt; Threads" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Threads" />
      <MemberSignature Language="VB.NET" Value="Public Property Threads As IList(Of ProcessThreadInfo)" />
      <MemberSignature Language="F#" Value="member this.Threads : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.Threads" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.threads")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-173">Abrufen oder Festlegen der Threadliste.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-173">Gets or sets thread list.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeStamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-174">Ruft ab, oder legt ihn fest Zeitstempel.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-174">Gets or sets time stamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalProcessorTime">
      <MemberSignature Language="C#" Value="public string TotalProcessorTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TotalProcessorTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.TotalProcessorTime" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalProcessorTime As String" />
      <MemberSignature Language="F#" Value="member this.TotalProcessorTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.TotalProcessorTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalProcessorTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-175">Ruft ab oder legt die CPU-Gesamtzeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-175">Gets or sets total CPU time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-176">Ruft ab oder legt Benutzernamen fest.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-176">Gets or sets user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserProcessorTime">
      <MemberSignature Language="C#" Value="public string UserProcessorTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserProcessorTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.UserProcessorTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UserProcessorTime As String" />
      <MemberSignature Language="F#" Value="member this.UserProcessorTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.UserProcessorTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userProcessorTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-177">Ruft ab, oder legt ihn fest Benutzer CPU-Zeit.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-177">Gets or sets user CPU time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMemorySize64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; VirtualMemorySize64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; VirtualMemorySize64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.VirtualMemorySize64" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMemorySize64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.VirtualMemorySize64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.VirtualMemorySize64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMemorySize64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-178">Ruft ab oder legt die Größe des virtuellen Speichers.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-178">Gets or sets virtual memory size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkingSet64">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; WorkingSet64 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; WorkingSet64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessInfo.WorkingSet64" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkingSet64 As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.WorkingSet64 : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessInfo.WorkingSet64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workingSet64")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c6b3-179">Ruft ab, oder legt ihn fest Workingsets.</span><span class="sxs-lookup"><span data-stu-id="3c6b3-179">Gets or sets working set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>