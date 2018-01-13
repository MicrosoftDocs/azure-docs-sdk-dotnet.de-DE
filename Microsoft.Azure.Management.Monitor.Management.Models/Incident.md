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
            <span data-ttu-id="7e083-101">Ein alert Incident gibt den Aktivierungsstatus von Warnungsregel an.</span><span class="sxs-lookup"><span data-stu-id="7e083-101">An alert incident indicates the activation status of an alert rule.</span></span>
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
            <span data-ttu-id="7e083-102">Initialisiert eine neue Instanz der Klasse Incident an.</span><span class="sxs-lookup"><span data-stu-id="7e083-102">Initializes a new instance of the Incident class.</span></span>
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
        <param name="name"><span data-ttu-id="7e083-103">Incident Name.</span><span class="sxs-lookup"><span data-stu-id="7e083-103">Incident name.</span></span></param>
        <param name="ruleName"><span data-ttu-id="7e083-104">Der Name der Regel, die dem Vorfall zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="7e083-104">Rule name that is associated with the incident.</span></span></param>
        <param name="isActive"><span data-ttu-id="7e083-105">Ein boolescher Wert, um anzugeben, ob der Vorfall aktiv ist oder gelöst ist.</span><span class="sxs-lookup"><span data-stu-id="7e083-105">A boolean to indicate whether the incident is active or resolved.</span></span></param>
        <param name="activatedTime"><span data-ttu-id="7e083-106">Der Zeitpunkt, zu dem der Vorfall im ISO8601-Format aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="7e083-106">The time at which the incident was activated in ISO8601 format.</span></span></param>
        <param name="resolvedTime"><span data-ttu-id="7e083-107">Der Zeitpunkt, an dem der Incident, im ISO8601-Format aufgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="7e083-107">The time at which the incident was resolved in ISO8601 format.</span></span> <span data-ttu-id="7e083-108">Wenn null ist, bedeutet dies, dass der Incident noch aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="7e083-108">If null, it means the incident is still active.</span></span></param>
        <summary>
            <span data-ttu-id="7e083-109">Initialisiert eine neue Instanz der Klasse Incident an.</span><span class="sxs-lookup"><span data-stu-id="7e083-109">Initializes a new instance of the Incident class.</span></span>
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
            <span data-ttu-id="7e083-110">Ruft den Zeitpunkt, zu dem der Vorfall im ISO8601-Format aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="7e083-110">Gets the time at which the incident was activated in ISO8601 format.</span></span>
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
            <span data-ttu-id="7e083-111">Ruft einen booleschen Wert an, ob der Vorfall aktiv ist oder gelöst ist.</span><span class="sxs-lookup"><span data-stu-id="7e083-111">Gets a boolean to indicate whether the incident is active or resolved.</span></span>
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
            <span data-ttu-id="7e083-112">Ruft Incident Namen ab.</span><span class="sxs-lookup"><span data-stu-id="7e083-112">Gets incident name.</span></span>
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
            <span data-ttu-id="7e083-113">Ruft den Zeitpunkt, an dem der Incident, im ISO8601-Format aufgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="7e083-113">Gets the time at which the incident was resolved in ISO8601 format.</span></span>
            <span data-ttu-id="7e083-114">Wenn null ist, bedeutet dies, dass der Incident noch aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="7e083-114">If null, it means the incident is still active.</span></span>
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
            <span data-ttu-id="7e083-115">Ruft die Regelnamen, der mit dem Vorfall zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="7e083-115">Gets rule name that is associated with the incident.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>