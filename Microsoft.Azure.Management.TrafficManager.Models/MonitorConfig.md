<Type Name="MonitorConfig" FullName="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig">
  <TypeSignature Language="C#" Value="public class MonitorConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MonitorConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class MonitorConfig" />
  <TypeSignature Language="F#" Value="type MonitorConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Klasse, die Einstellungen in einem Traffic Manager-Profil für die endpunktüberwachung enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitorConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MonitorConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitorConfig (string profileMonitorStatus = null, string protocol = null, Nullable&lt;long&gt; port = null, string path = null, Nullable&lt;long&gt; intervalInSeconds = null, Nullable&lt;long&gt; timeoutInSeconds = null, Nullable&lt;long&gt; toleratedNumberOfFailures = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string profileMonitorStatus, string protocol, valuetype System.Nullable`1&lt;int64&gt; port, string path, valuetype System.Nullable`1&lt;int64&gt; intervalInSeconds, valuetype System.Nullable`1&lt;int64&gt; timeoutInSeconds, valuetype System.Nullable`1&lt;int64&gt; toleratedNumberOfFailures) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.#ctor(System.String,System.String,System.Nullable{System.Int64},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional profileMonitorStatus As String = null, Optional protocol As String = null, Optional port As Nullable(Of Long) = null, Optional path As String = null, Optional intervalInSeconds As Nullable(Of Long) = null, Optional timeoutInSeconds As Nullable(Of Long) = null, Optional toleratedNumberOfFailures As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig : string * string * Nullable&lt;int64&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig" Usage="new Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig (profileMonitorStatus, protocol, port, path, intervalInSeconds, timeoutInSeconds, toleratedNumberOfFailures)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="profileMonitorStatus" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="intervalInSeconds" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="timeoutInSeconds" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="toleratedNumberOfFailures" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="profileMonitorStatus">Ruft ab, oder legt ihn fest-Messagingeigenschaften auf Profilebene Überwachungsstatus Traffic Manager-Profils.</param>
        <param name="protocol">Abrufen oder Festlegen des Protokolls (HTTP, HTTPS oder TCP), um für die Suche nach endpunktzuständen verwendet.</param>
        <param name="port">Ruft ab oder legt den TCP-Port verwendet, um für die Suche nach endpunktzuständen.</param>
        <param name="path">Ruft ab oder legt den Pfad relativ zum Domänennamen Endpunkts verwendet, um für die Suche nach endpunktzuständen fest.</param>
        <param name="intervalInSeconds">Ruft ab oder legt das monitorintervall für Endpunkte in diesem Profil. Dies ist das Intervall, in dem Traffic Manager die Integrität jeder Endpunkt in diesem Profil prüft.</param>
        <param name="timeoutInSeconds">Ruft ab oder legt die Monitor-zeitüberschreitung für Endpunkte in diesem Profil. Dies ist die Zeit, die Traffic Manager Endpunkten in dieses Profil, um als Antwort auf die integritätsprüfung durchgeführt werden können.</param>
        <param name="toleratedNumberOfFailures">Ruft ab oder legt die Anzahl der aufeinanderfolgenden fehlerhaften integritätsprüfung, die Traffic Manager unvollständige, bevor Sie einen Endpunkt in diesem Profil Degraded deklarieren, nach dem nächsten integritätsprüfung fehlgeschlagen.</param>
        <summary>
            Initialisiert eine neue Instanz der MonitorConfig-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IntervalInSeconds As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.IntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="intervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das monitorintervall für Endpunkte in diesem Profil.
            Dies ist das Intervall, in dem Traffic Manager die Integrität jeder Endpunkt in diesem Profil prüft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad relativ zum Domänennamen Endpunkts verwendet, um für die Suche nach endpunktzuständen fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den TCP-Port verwendet, um für die Suche nach endpunktzuständen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProfileMonitorStatus">
      <MemberSignature Language="C#" Value="public string ProfileMonitorStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProfileMonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.ProfileMonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProfileMonitorStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProfileMonitorStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.ProfileMonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="profileMonitorStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Messagingeigenschaften auf Profilebene Überwachungsstatus Traffic Manager-Profils.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Protokolls (HTTP, HTTPS oder TCP), um für die Suche nach endpunktzuständen verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.TimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeoutInSeconds As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TimeoutInSeconds : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.TimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeoutInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Monitor-zeitüberschreitung für Endpunkte in diesem Profil.
            Dies ist die Zeit, die Traffic Manager Endpunkten in dieses Profil, um als Antwort auf die integritätsprüfung durchgeführt werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToleratedNumberOfFailures">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ToleratedNumberOfFailures { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ToleratedNumberOfFailures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.ToleratedNumberOfFailures" />
      <MemberSignature Language="VB.NET" Value="Public Property ToleratedNumberOfFailures As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ToleratedNumberOfFailures : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig.ToleratedNumberOfFailures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="toleratedNumberOfFailures")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der aufeinanderfolgenden fehlerhaften integritätsprüfung, die Traffic Manager unvollständige, bevor Sie einen Endpunkt in diesem Profil Degraded deklarieren, nach dem nächsten integritätsprüfung fehlgeschlagen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>