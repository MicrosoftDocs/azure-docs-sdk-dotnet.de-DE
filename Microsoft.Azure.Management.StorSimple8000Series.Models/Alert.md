<Type Name="Alert" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert">
  <TypeSignature Language="C#" Value="public class Alert : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Alert extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert" />
  <TypeSignature Language="VB.NET" Value="Public Class Alert&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Alert = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Warnung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Alert ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Warnungs-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Alert (string title, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope scope, string alertType, DateTime appearedAtTime, DateTime appearedAtSourceTime, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource source, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity severity, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus status, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; clearedAtTime = null, Nullable&lt;DateTime&gt; clearedAtSourceTime = null, string recommendation = null, string resolutionReason = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails errorDetails = null, System.Collections.Generic.IDictionary&lt;string,string&gt; detailedInformation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string title, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope scope, string alertType, valuetype System.DateTime appearedAtTime, valuetype System.DateTime appearedAtSourceTime, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource source, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity severity, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus status, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; clearedAtTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; clearedAtSourceTime, string recommendation, string resolutionReason, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails errorDetails, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; detailedInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope,System.String,System.DateTime,System.DateTime,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (title As String, scope As AlertScope, alertType As String, appearedAtTime As DateTime, appearedAtSourceTime As DateTime, source As AlertSource, severity As AlertSeverity, status As AlertStatus, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional clearedAtTime As Nullable(Of DateTime) = null, Optional clearedAtSourceTime As Nullable(Of DateTime) = null, Optional recommendation As String = null, Optional resolutionReason As String = null, Optional errorDetails As AlertErrorDetails = null, Optional detailedInformation As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Alert : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope * string * DateTime * DateTime * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Alert" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Alert (title, scope, alertType, appearedAtTime, appearedAtSourceTime, source, severity, status, id, name, type, kind, clearedAtTime, clearedAtSourceTime, recommendation, resolutionReason, errorDetails, detailedInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="title" Type="System.String" />
        <Parameter Name="scope" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope" />
        <Parameter Name="alertType" Type="System.String" />
        <Parameter Name="appearedAtTime" Type="System.DateTime" />
        <Parameter Name="appearedAtSourceTime" Type="System.DateTime" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource" />
        <Parameter Name="severity" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="clearedAtTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="clearedAtSourceTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recommendation" Type="System.String" />
        <Parameter Name="resolutionReason" Type="System.String" />
        <Parameter Name="errorDetails" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails" />
        <Parameter Name="detailedInformation" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="title">Der Titel der Warnung</param>
        <param name="scope">Der Bereich der Warnung. Folgende Werte sind möglich: "Resource", "Gerät"</param>
        <param name="alertType">Der Typ der Warnung</param>
        <param name="appearedAtTime">Die UTC-Zeit, an der die Warnung ausgelöst wurde</param>
        <param name="appearedAtSourceTime">Die Quellzeit, an der die Warnung ausgelöst wurde</param>
        <param name="source">Die Quelle, an der die Warnung ausgelöst wurde</param>
        <param name="severity">Der Schweregrad der Warnung. Folgende Werte sind möglich: "Information", "Warnung", "Kritisch"</param>
        <param name="status">Der aktuelle Status der Warnung. Folgende Werte sind möglich: "Aktiv", "Deaktiviert"</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="clearedAtTime">Die UTC-Zeit, an der die Warnung gelöscht wurde</param>
        <param name="clearedAtSourceTime">Die Quellzeit, an der die Warnung gelöscht wurde</param>
        <param name="recommendation">Die empfohlene Aktion für das Problem in der Warnung ausgelöst</param>
        <param name="resolutionReason">Der Grund für die Behandlung der Warnung</param>
        <param name="errorDetails">Die Details des Fehlers für die die Warnung ausgelöst wurde</param>
        <param name="detailedInformation">Weitere Details zur Warnung</param>
        <summary>
            Initialisiert eine neue Instanz der Warnungs-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertType">
      <MemberSignature Language="C#" Value="public string AlertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AlertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AlertType As String" />
      <MemberSignature Language="F#" Value="member this.AlertType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AlertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alertType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Warnung fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedAtSourceTime">
      <MemberSignature Language="C#" Value="public DateTime AppearedAtSourceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AppearedAtSourceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtSourceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedAtSourceTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.AppearedAtSourceTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtSourceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appearedAtSourceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Quellzeit, an der die Warnung ausgelöst wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedAtTime">
      <MemberSignature Language="C#" Value="public DateTime AppearedAtTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AppearedAtTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedAtTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.AppearedAtTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appearedAtTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die UTC-Zeit, an der die Warnung ausgelöst wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearedAtSourceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClearedAtSourceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClearedAtSourceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtSourceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ClearedAtSourceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClearedAtSourceTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtSourceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clearedAtSourceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Quellzeit, an der die Warnung gelöscht wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearedAtTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClearedAtTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClearedAtTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ClearedAtTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClearedAtTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clearedAtTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die UTC-Zeit, an der die Warnung gelöscht wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedInformation">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; DetailedInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; DetailedInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.DetailedInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedInformation As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.DetailedInformation : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.DetailedInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedInformation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Weitere Details zur Warnung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As AlertErrorDetails" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Details des Fehlers für die die Warnung ausgelöst wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendation">
      <MemberSignature Language="C#" Value="public string Recommendation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Recommendation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Recommendation" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendation As String" />
      <MemberSignature Language="F#" Value="member this.Recommendation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Recommendation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die empfohlene Aktion für das Problem in der Warnung ausgelöst
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolutionReason">
      <MemberSignature Language="C#" Value="public string ResolutionReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResolutionReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ResolutionReason" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolutionReason As String" />
      <MemberSignature Language="F#" Value="member this.ResolutionReason : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ResolutionReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resolutionReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Grund für die Behandlung der Warnung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As AlertScope" />
      <MemberSignature Language="F#" Value="member this.Scope : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Bereich der Warnung. Folgende Werte sind möglich: "Resource", "Gerät"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity Severity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Severity" />
      <MemberSignature Language="VB.NET" Value="Public Property Severity As AlertSeverity" />
      <MemberSignature Language="F#" Value="member this.Severity : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schweregrad der Warnung. Folgende Werte sind möglich: "Information", "Warnung", "Kritisch"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As AlertSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Quelle, an der die Warnung ausgelöst wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As AlertStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Status der Warnung. Folgende Werte sind möglich: "Aktiv", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.title")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Titel der Warnung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="alert.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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