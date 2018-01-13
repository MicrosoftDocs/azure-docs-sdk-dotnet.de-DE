<Type Name="Incident" FullName="Microsoft.Azure.Management.Monitor.Management.Models.Incident">
  <TypeSignature Language="C#" Value="public class Incident" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Incident extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.Incident" />
  <TypeSignature Language="VB.NET" Value="Public Class Incident" />
  <TypeSignature Language="F#" Value="type Incident = class" />
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
            Ein alert Incident gibt den Aktivierungsstatus von Warnungsregel an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Incident ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Incident.#ctor" />
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
            Initialisiert eine neue Instanz der Klasse Incident an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Incident (string name = null, string ruleName = null, Nullable&lt;bool&gt; isActive = null, Nullable&lt;DateTime&gt; activatedTime = null, Nullable&lt;DateTime&gt; resolvedTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string ruleName, valuetype System.Nullable`1&lt;bool&gt; isActive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; activatedTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; resolvedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Incident.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional ruleName As String = null, Optional isActive As Nullable(Of Boolean) = null, Optional activatedTime As Nullable(Of DateTime) = null, Optional resolvedTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.Incident : string * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.Incident" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.Incident (name, ruleName, isActive, activatedTime, resolvedTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="isActive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="activatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resolvedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Incident Name.</param>
        <param name="ruleName">Der Name der Regel, die dem Vorfall zugeordnet ist.</param>
        <param name="isActive">Ein boolescher Wert, um anzugeben, ob der Vorfall aktiv ist oder gelöst ist.</param>
        <param name="activatedTime">Der Zeitpunkt, zu dem der Vorfall im ISO8601-Format aktiviert wurde.</param>
        <param name="resolvedTime">Der Zeitpunkt, an dem der Incident, im ISO8601-Format aufgelöst wurde. Wenn null ist, bedeutet dies, dass der Incident noch aktiv ist.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Incident an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ActivatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ActivatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.ActivatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ActivatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.ActivatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, zu dem der Vorfall im ISO8601-Format aktiviert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsActive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.IsActive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsActive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsActive : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.IsActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isActive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen booleschen Wert an, ob der Vorfall aktiv ist oder gelöst ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Incident Namen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ResolvedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ResolvedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.ResolvedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResolvedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ResolvedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.ResolvedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolvedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem der Incident, im ISO8601-Format aufgelöst wurde.
            Wenn null ist, bedeutet dies, dass der Incident noch aktiv ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleName">
      <MemberSignature Language="C#" Value="public string RuleName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.RuleName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuleName As String" />
      <MemberSignature Language="F#" Value="member this.RuleName : string" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.RuleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Regelnamen, der mit dem Vorfall zugeordnet ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>