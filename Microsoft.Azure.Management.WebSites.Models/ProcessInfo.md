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
            Prozess-Informationen.
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
            Initialisiert eine neue Instanz der Klasse ProcessInfo an.
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
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="processInfoId">ARM-Bezeichner für die Bereitstellung.</param>
        <param name="processInfoName">Bereitstellungsname.</param>
        <param name="href">HRef-URI.</param>
        <param name="miniDump">Minidump-URI.</param>
        <param name="isProfileRunning">Werden Profil wird ausgeführt?</param>
        <param name="isIisProfileRunning">Werden das IIS-Profil wird ausgeführt?</param>
        <param name="iisProfileTimeoutInSeconds">Profil für die IIS-Timeout (Sekunden).</param>
        <param name="parent">Übergeordnete Prozess.</param>
        <param name="children">Liste der untergeordneten Prozess.</param>
        <param name="threads">Threadliste.</param>
        <param name="openFileHandles">Liste der geöffneten Dateien.</param>
        <param name="modules">Die Liste der Module.</param>
        <param name="fileName">Der Dateiname dieses Prozesses.</param>
        <param name="commandLine">Über die Befehlszeile.</param>
        <param name="userName">Benutzername.</param>
        <param name="handleCount">Anzahl der Handles.</param>
        <param name="moduleCount">Anzahl der Module.</param>
        <param name="threadCount">Anzahl der Threads.</param>
        <param name="startTime">Die Startzeit.</param>
        <param name="totalProcessorTime">Gesamte CPU-Zeit.</param>
        <param name="userProcessorTime">Benutzer-CPU-Zeit.</param>
        <param name="privilegedProcessorTime">Privilegierte CPU-Zeit.</param>
        <param name="workingSet64">Workingset.</param>
        <param name="peakWorkingSet64">Peak Workingsets.</param>
        <param name="privateMemorySize64">Größe des privaten Speichers.</param>
        <param name="virtualMemorySize64">Die Größe des virtuellen Speichers.</param>
        <param name="peakVirtualMemorySize64">Maximale Auslastung des virtuellen Speichers.</param>
        <param name="pagedSystemMemorySize64">Ausgelagerten Systemspeichers.</param>
        <param name="nonpagedSystemMemorySize64">Nicht ausgelagerten Systemspeichers.</param>
        <param name="pagedMemorySize64">Ausgelagerte Arbeitsspeicher.</param>
        <param name="peakPagedMemorySize64">Die maximale ausgelagerten Arbeitsspeichers.</param>
        <param name="timeStamp">Zeitstempel.</param>
        <param name="environmentVariables">Liste von Umgebungsvariablen.</param>
        <param name="isScmSite">Handelt es sich um den SCM Standort?</param>
        <param name="isWebJob">Handelt es sich um einen Webauftrag?</param>
        <param name="description">Beschreibung des Prozesses.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse ProcessInfo an.
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
            Abrufen oder Festlegen der Liste der untergeordneten Prozess.
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
            Ruft ab, oder legt die Befehlszeile fest.
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
            Ruft ab oder legt die Beschreibung des Prozesses.
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
            Ruft ab oder legt die Liste von Umgebungsvariablen.
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
            Ruft ab oder legt den Namen dieses Vorgangs fest.
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
            Ruft ab oder legt die maximale Handleanzahl beträgt.
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
            Ruft ab, oder legt ihn fest hRef URI.
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
            Abrufen oder Festlegen der IIS-Profil-Timeout (Sekunden).
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
            Ruft ab oder legt ihn fest ist das IIS-Profil ausgeführt?
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
            Ruft ab oder legt ihn fest ist Profil ausgeführt?
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
            Ruft ab oder legt ihn fest ist dies der SCM-Standort?
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
            Ruft ab oder legt ihn fest ist dies einen Webauftrag?
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
            Ruft ab, oder legt ihn fest Minidump URI.
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
            Ruft ab, oder legt ihn fest Modulanzahl.
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
            Ruft ab oder legt die Liste der Module fest.
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
            Ruft ab oder legt des nicht ausgelagerten Systemspeichers.
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
            Ruft ab oder legt die Liste der geöffneten Dateien.
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
            Ruft ab, oder legt ihn fest Auslagerungsspeichers.
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
            Ruft ab, oder legt ihn fest ausgelagerten Systemspeichers.
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
            Ruft ab, oder legt ihn fest übergeordneten Prozess.
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
            Ruft ab, oder legt ihn fest Spitzenzeiten des ausgelagerten Arbeitsspeichers.
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
            Ruft ab, oder legt ihn fest spitzenauslastung des virtuellen Arbeitsspeichers.
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
            Ruft ab, oder legt ihn fest Peak Workingsets.
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
            Ruft ab oder legt die Größe des privaten Speichers.
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
            Ruft ab, oder legt ihn fest privilegierte CPU-Zeit.
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
            Ruft ab oder legt ARM-Bezeichner für die Bereitstellung.
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
            Ruft ab, oder legt ihn fest Bereitstellungsname.
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
            Ruft ab oder legt die Startzeit.
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
            Ruft ab oder legt die Anzahl der Threads fest.
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
            Abrufen oder Festlegen der Threadliste.
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
            Ruft ab, oder legt ihn fest Zeitstempel.
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
            Ruft ab oder legt die CPU-Gesamtzeit.
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
            Ruft ab oder legt Benutzernamen fest.
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
            Ruft ab, oder legt ihn fest Benutzer CPU-Zeit.
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
            Ruft ab oder legt die Größe des virtuellen Speichers.
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
            Ruft ab, oder legt ihn fest Workingsets.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>