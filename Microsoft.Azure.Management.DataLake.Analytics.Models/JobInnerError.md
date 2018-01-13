<Type Name="JobInnerError" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError">
  <TypeSignature Language="C#" Value="public class JobInnerError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobInnerError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" />
  <TypeSignature Language="VB.NET" Value="Public Class JobInnerError" />
  <TypeSignature Language="F#" Value="type JobInnerError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Fehlerdetails für den Data Lake Analytics-Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInnerError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobInnerError-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInnerError (Nullable&lt;int&gt; diagnosticCode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity = null, string details = null, string component = null, string errorId = null, string helpLink = null, string internalDiagnostics = null, string message = null, string resolution = null, string source = null, string description = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; diagnosticCode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity, string details, string component, string errorId, string helpLink, string internalDiagnostics, string message, string resolution, string source, string description, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.#ctor(System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes},System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional diagnosticCode As Nullable(Of Integer) = null, Optional severity As Nullable(Of SeverityTypes) = null, Optional details As String = null, Optional component As String = null, Optional errorId As String = null, Optional helpLink As String = null, Optional internalDiagnostics As String = null, Optional message As String = null, Optional resolution As String = null, Optional source As String = null, Optional description As String = null, Optional innerError As JobInnerError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError : Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; * string * string * string * string * string * string * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError (diagnosticCode, severity, details, component, errorId, helpLink, internalDiagnostics, message, resolution, source, description, innerError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="diagnosticCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" />
        <Parameter Name="details" Type="System.String" />
        <Parameter Name="component" Type="System.String" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="helpLink" Type="System.String" />
        <Parameter Name="internalDiagnostics" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="resolution" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="innerError" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" />
      </Parameters>
      <Docs>
        <param name="diagnosticCode">der Diagnose Fehlercode.</param>
        <param name="severity">Der Schweregrad des Fehlers. Folgende Werte sind möglich: "Warnung", "Fehler", "Info", "SevereWarning", "Veraltet", "UserWarning"</param>
        <param name="details">die Details der Fehlermeldung.</param>
        <param name="component">die Komponente, die nicht bestanden.</param>
        <param name="errorId">der spezifische Bezeichner für den Typ der Fehler im Auftrag.</param>
        <param name="helpLink">der Link, um die MSDN oder Azure Hilfe für diese Art von Fehlern, sofern vorhanden.</param>
        <param name="internalDiagnostics">die interne Diagnose stapelüberwachung, wenn der Benutzer anfordern die Fehlerdetails des Auftrags über ausreichende Berechtigungen verfügt, die er abgerufen wird, wird andernfalls leer sein.</param>
        <param name="message">die Benutzer-friendly-Fehlermeldung für den Fehler.</param>
        <param name="resolution">die empfohlene Lösung für den Fehler, falls vorhanden.</param>
        <param name="source">die ultimative Quelle des Fehlers (normalerweise SYSTEM oder Benutzer).</param>
        <param name="description">die Beschreibung der Fehlermeldung</param>
        <param name="innerError">der interne Fehler dieser bestimmten Auftrag Fehlermeldung, falls vorhanden.</param>
        <summary>
            Initialisiert eine neue Instanz der JobInnerError-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Component" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Component" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="component")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Komponente, die Fehler ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Beschreibung der Fehlermeldung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Details der Fehlermeldung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiagnosticCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiagnosticCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.DiagnosticCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiagnosticCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.DiagnosticCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnosticCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Diagnose-Fehlercode ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.ErrorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den bestimmten Bezeichner für den Typ der Fehler im Auftrag ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HelpLink">
      <MemberSignature Language="C#" Value="public string HelpLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HelpLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.HelpLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HelpLink As String" />
      <MemberSignature Language="F#" Value="member this.HelpLink : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.HelpLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="helpLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Link, um die MSDN oder Azure-Hilfe für diese Art von Fehlern, gegebenenfalls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InnerError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InnerError As JobInnerError" />
      <MemberSignature Language="F#" Value="member this.InnerError : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InnerError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innerError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den inneren Fehler dieser Fehlermeldung bestimmten Auftrag ab, sofern vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDiagnostics">
      <MemberSignature Language="C#" Value="public string InternalDiagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InternalDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalDiagnostics As String" />
      <MemberSignature Language="F#" Value="member this.InternalDiagnostics : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InternalDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die interne Diagnose stapelüberwachung ab, wenn der Benutzer anfordern, die Fehlerdetails des Auftrags verfügt über ausreichende Berechtigungen, die er abgerufen werden sollen, andernfalls er leer sein wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Benutzer benutzerfreundliche Fehlermeldung für den Fehler an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resolution">
      <MemberSignature Language="C#" Value="public string Resolution { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resolution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Resolution" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resolution As String" />
      <MemberSignature Language="F#" Value="member this.Resolution : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Resolution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ggf. die empfohlene Lösung des Fehlers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As Nullable(Of SeverityTypes)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Schweregrad des Fehlers ab. Folgende Werte sind möglich: "Warnung", "Fehler", "Info", "SevereWarning", "Veraltet", "UserWarning"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ultimative Quelle des Fehlers ab (normalerweise SYSTEM oder Benutzer).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>