<Type Name="USqlJobProperties" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties">
  <TypeSignature Language="C#" Value="public class USqlJobProperties : Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlJobProperties extends Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlJobProperties&#xA;Inherits JobProperties" />
  <TypeSignature Language="F#" Value="type USqlJobProperties = class&#xA;    inherit JobProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("USql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eigenschaften der U-SQL-Auftrag beim Abrufen der U-SQL-Aufträge verwendet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlJobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der USqlJobProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlJobProperties (string script, string runtimeVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; resources = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics statistics = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath debugData = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; diagnostics = null, string algebraFilePath = null, Nullable&lt;TimeSpan&gt; totalCompilationTime = null, Nullable&lt;TimeSpan&gt; totalPauseTime = null, Nullable&lt;TimeSpan&gt; totalQueuedTime = null, Nullable&lt;TimeSpan&gt; totalRunningTime = null, string rootProcessNodeId = null, string yarnApplicationId = null, Nullable&lt;long&gt; yarnApplicationTimeStamp = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; compileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, string runtimeVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; resources, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics statistics, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath debugData, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; diagnostics, string algebraFilePath, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalCompilationTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalPauseTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalQueuedTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalRunningTime, string rootProcessNodeId, string yarnApplicationId, valuetype System.Nullable`1&lt;int64&gt; yarnApplicationTimeStamp, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; compileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource},Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics,Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics},System.String,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String, Optional runtimeVersion As String = null, Optional resources As IList(Of JobResource) = null, Optional statistics As JobStatistics = null, Optional debugData As JobDataPath = null, Optional diagnostics As IList(Of Diagnostics) = null, Optional algebraFilePath As String = null, Optional totalCompilationTime As Nullable(Of TimeSpan) = null, Optional totalPauseTime As Nullable(Of TimeSpan) = null, Optional totalQueuedTime As Nullable(Of TimeSpan) = null, Optional totalRunningTime As Nullable(Of TimeSpan) = null, Optional rootProcessNodeId As String = null, Optional yarnApplicationId As String = null, Optional yarnApplicationTimeStamp As Nullable(Of Long) = null, Optional compileMode As Nullable(Of CompileMode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics * Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; * string * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties (script, runtimeVersion, resources, statistics, debugData, diagnostics, algebraFilePath, totalCompilationTime, totalPauseTime, totalQueuedTime, totalRunningTime, rootProcessNodeId, yarnApplicationId, yarnApplicationTimeStamp, compileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt;" />
        <Parameter Name="statistics" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics" />
        <Parameter Name="debugData" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath" />
        <Parameter Name="diagnostics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt;" />
        <Parameter Name="algebraFilePath" Type="System.String" />
        <Parameter Name="totalCompilationTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalPauseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalQueuedTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalRunningTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="rootProcessNodeId" Type="System.String" />
        <Parameter Name="yarnApplicationId" Type="System.String" />
        <Parameter Name="yarnApplicationTimeStamp" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="compileMode" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;" />
      </Parameters>
      <Docs>
        <param name="script">das auszuführende Skript</param>
        <param name="runtimeVersion">die Common Language Runtime-Version des Data Lake Analytics-Moduls für den spezifischen Typ der ausgeführten Auftrags verwenden.</param>
        <param name="resources">die Liste der Ressourcen, die vom Auftrag erforderlich sind</param>
        <param name="statistics">der Auftrag Statistiken.</param>
        <param name="debugData">die Datenspeicherorte für den Auftrag bestimmte Debuggen.</param>
        <param name="diagnostics">die Diagnose für den Auftrag.</param>
        <param name="algebraFilePath">der Dateipfad Algebra verglichen werden, nachdem der Auftrag abgeschlossen wurde</param>
        <param name="totalCompilationTime">die gesamte Zeitdauer für diesen Auftrag kompilieren. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="totalPauseTime">die gesamte Zeitdauer dieser Auftrag wurde angehalten.
            Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="totalQueuedTime">die gesamte Zeitdauer dieser Auftrag in die Warteschlange eingereiht.
            Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="totalRunningTime">die gesamte Zeitdauer für diesen Auftrag ausführen. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="rootProcessNodeId">die ID zur Identifizierung des Auftrags-Managers Koordinieren der Ausführung eines Auftrags. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="yarnApplicationId">die ID zum Identifizieren der Yarn-Anwendung, die Ausführung des Auftrags verwendet. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="yarnApplicationTimeStamp">der Zeitstempel (in Takten) für die Ausführung des Auftrags Yarn-Anwendung. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.</param>
        <param name="compileMode">der spezifische Kompilierungsmodus für den Auftrag, der während der Ausführung verwendet. Wenn dies während der Übermittlung nicht angegeben ist, wird der Server die optimale Kompilierungsmodus bestimmen. Folgende Werte sind möglich: 'Semantisch', 'Full', 'SingleBox'</param>
        <summary>
            Initialisiert eine neue Instanz der USqlJobProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlgebraFilePath">
      <MemberSignature Language="C#" Value="public string AlgebraFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlgebraFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.AlgebraFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlgebraFilePath As String" />
      <MemberSignature Language="F#" Value="member this.AlgebraFilePath : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.AlgebraFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="algebraFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Pfad Algebra ab, nachdem der Auftrag abgeschlossen wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompileMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; CompileMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt; CompileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.CompileMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompileMode As Nullable(Of CompileMode)" />
      <MemberSignature Language="F#" Value="member this.CompileMode : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.CompileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="compileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.CompileMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den bestimmten Kompilierungsmodus für den Auftrag, der während der Ausführung verwendet. Wenn dies während der Übermittlung nicht angegeben ist, wird der Server die optimale Kompilierungsmodus bestimmen. Folgende Werte sind möglich: 'Semantisch', 'Full', 'SingleBox'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DebugData">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath DebugData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath DebugData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.DebugData" />
      <MemberSignature Language="VB.NET" Value="Public Property DebugData As JobDataPath" />
      <MemberSignature Language="F#" Value="member this.DebugData : Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.DebugData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="debugData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Auftrags Datenspeicherorte bestimmte Debuggen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt; Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As IList(Of Diagnostics)" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Diagnose für den Auftrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of JobResource)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Ressourcen, die vom Auftrag erforderlich sind
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RootProcessNodeId">
      <MemberSignature Language="C#" Value="public string RootProcessNodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RootProcessNodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.RootProcessNodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RootProcessNodeId As String" />
      <MemberSignature Language="F#" Value="member this.RootProcessNodeId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.RootProcessNodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rootProcessNodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID zur Identifizierung des Auftrags-Manager koordinierende die Ausführung des Auftrags. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics Statistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public Property Statistics As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statistics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Auftragsstatistik bestimmten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCompilationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalCompilationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalCompilationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalCompilationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCompilationTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalCompilationTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalCompilationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalCompilationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte Zeitdauer dieser Auftrag kompilieren. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalPauseTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalPauseTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalPauseTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalPauseTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalPauseTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalPauseTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalPauseTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalPauseTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte Zeitdauer dieser Auftrag angehalten. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalQueuedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalQueuedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalQueuedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalQueuedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalQueuedTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalQueuedTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalQueuedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalQueuedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte Zeitdauer dieser Auftrag in der Warteschlange ab. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalRunningTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalRunningTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalRunningTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalRunningTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalRunningTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalRunningTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.TotalRunningTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalRunningTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte Zeitdauer dieser Auftrag ausgeführt. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="uSqlJobProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
    <Member MemberName="YarnApplicationId">
      <MemberSignature Language="C#" Value="public string YarnApplicationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string YarnApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property YarnApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.YarnApplicationId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="yarnApplicationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID zum Identifizieren der Yarn-Anwendung, die Ausführung des Auftrags verwendet. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="YarnApplicationTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; YarnApplicationTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; YarnApplicationTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property YarnApplicationTimeStamp As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.YarnApplicationTimeStamp : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlJobProperties.YarnApplicationTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="yarnApplicationTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitstempel (in Takten) für die Ausführung des Auftrags Yarn-Anwendung ab. Dieser Wert sollte nicht vom Benutzer festgelegt werden und werden ignoriert, wenn es sich handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>