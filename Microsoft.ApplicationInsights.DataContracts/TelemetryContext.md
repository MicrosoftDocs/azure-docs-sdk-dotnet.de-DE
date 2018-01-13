<Type Name="TelemetryContext" FullName="Microsoft.ApplicationInsights.DataContracts.TelemetryContext">
  <TypeSignature Language="C#" Value="public sealed class TelemetryContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TelemetryContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TelemetryContext" />
  <TypeSignature Language="F#" Value="type TelemetryContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Kontext für das Senden von Telemetriedaten an Application Insights-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cloud">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.CloudContext Cloud { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.CloudContext Cloud" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Cloud" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Cloud As CloudContext" />
      <MemberSignature Language="F#" Value="member this.Cloud : Microsoft.ApplicationInsights.Extensibility.Implementation.CloudContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Cloud" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.CloudContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt ab, die die Cloud, die von diesem nachverfolgt beschreibt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.ComponentContext Component { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.ComponentContext Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Component" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Component As ComponentContext" />
      <MemberSignature Language="F#" Value="member this.Component : Microsoft.ApplicationInsights.Extensibility.Implementation.ComponentContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Component" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.ComponentContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt ab, beschreibt die Komponente, die von diesem nachverfolgt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Device">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.DeviceContext Device { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.DeviceContext Device" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Device" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Device As DeviceContext" />
      <MemberSignature Language="F#" Value="member this.Device : Microsoft.ApplicationInsights.Extensibility.Implementation.DeviceContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Device" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.DeviceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt, das nachverfolgt, die von diesem Gerät beschreibt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstrumentationKey">
      <MemberSignature Language="C#" Value="public string InstrumentationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstrumentationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.InstrumentationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property InstrumentationKey As String" />
      <MemberSignature Language="F#" Value="member this.InstrumentationKey : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.InstrumentationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Instrumentation Standardschlüssel für alle <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Objekte in diesem protokolliert <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>
            Standardmäßig ist diese Eigenschaft initialisiert, mit der <see cref="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.InstrumentationKey" /> Wert der <see cref="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" /> Instanz <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />. Die Angabe ist für alle Telemetrie nachverfolgt, die über einen bestimmten <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> oder für einen bestimmten <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Instanz.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.LocationContext Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.LocationContext Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As LocationContext" />
      <MemberSignature Language="F#" Value="member this.Location : Microsoft.ApplicationInsights.Extensibility.Implementation.LocationContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.LocationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt ab, die einen nachverfolgt, die von diesem Speicherort beschreibt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As OperationContext" />
      <MemberSignature Language="F#" Value="member this.Operation : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt ab, die einen nachverfolgt, die von diesem Vorgang beschreibt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ein Wörterbuch von anwendungsdefinierten Eigenschaftswerte ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.SessionContext Session { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.SessionContext Session" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Session" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Session As SessionContext" />
      <MemberSignature Language="F#" Value="member this.Session : Microsoft.ApplicationInsights.Extensibility.Implementation.SessionContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.Session" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.SessionContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt ab, die eine nachverfolgt, die von dieser Sitzung des Benutzers beschreibt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="User">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext User { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext User" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.User" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property User As UserContext" />
      <MemberSignature Language="F#" Value="member this.User : Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext" Usage="Microsoft.ApplicationInsights.DataContracts.TelemetryContext.User" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Objekt ab, die einen Benutzer, die von diesem nachverfolgt beschreibt <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>