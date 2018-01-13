<Type Name="MetricAvailability" FullName="Microsoft.Azure.Management.Monitor.Models.MetricAvailability">
  <TypeSignature Language="C#" Value="public class MetricAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.MetricAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricAvailability" />
  <TypeSignature Language="F#" Value="type MetricAvailability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Metrik Verfügbarkeit gibt das zeitkorn (aggregationsintervall oder Häufigkeit) und die Beibehaltungsdauer für diese zeitkorn.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MetricAvailability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailability (Nullable&lt;TimeSpan&gt; timeGrain = null, Nullable&lt;TimeSpan&gt; retention = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeGrain, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retention) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricAvailability.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeGrain As Nullable(Of TimeSpan) = null, Optional retention As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.MetricAvailability : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.MetricAvailability" Usage="new Microsoft.Azure.Management.Monitor.Models.MetricAvailability (timeGrain, retention)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeGrain" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retention" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="timeGrain">Das zeitkorn gibt aggregationsintervalls für die Metrik an. Ausgedrückt als Dauer "PT1M", "P1D", usw.</param>
        <param name="retention">die Beibehaltungsdauer für die Metrik auf der angegebenen timegrain-Wert.  Ausgedrückt als Dauer "PT1M", "P1D", usw.</param>
        <summary>
            Initialisiert eine neue Instanz der MetricAvailability-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Retention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricAvailability.Retention" />
      <MemberSignature Language="VB.NET" Value="Public Property Retention As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Retention : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricAvailability.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die Beibehaltungsdauer für die Metrik auf der angegebenen timegrain-Wert.  Ausgedrückt als Dauer "PT1M", "P1D", usw.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricAvailability.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricAvailability.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder Festlegen der Zeit, die Auflösung aggregationsintervalls für die Metrik angibt. Ausgedrückt als Dauer "PT1M", "P1D", usw.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>