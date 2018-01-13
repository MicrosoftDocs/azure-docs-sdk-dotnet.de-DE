<Type Name="RollingUpgradeRunningStatus" FullName="Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus">
  <TypeSignature Language="C#" Value="public class RollingUpgradeRunningStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeRunningStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeRunningStatus" />
  <TypeSignature Language="F#" Value="type RollingUpgradeRunningStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Informationen zu den aktuellen Ausführungsstatus des gesamten Upgrades.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeRunningStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RollingUpgradeRunningStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeRunningStatus (Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt; code = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt; lastAction = null, Nullable&lt;DateTime&gt; lastActionTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt; code, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt; lastAction, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastActionTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As Nullable(Of RollingUpgradeStatusCode) = null, Optional startTime As Nullable(Of DateTime) = null, Optional lastAction As Nullable(Of RollingUpgradeActionType) = null, Optional lastActionTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus : Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus" Usage="new Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus (code, startTime, lastAction, lastActionTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastAction" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt;" />
        <Parameter Name="lastActionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="code">Code, der angibt, des aktuellen Status des Upgrades. Folgende Werte sind möglich: "RollingForward", "Abgebrochen", "Abgeschlossen", "Faulted"</param>
        <param name="startTime">Die Startzeit des Upgrades.</param>
        <param name="lastAction">Die letzte Aktion, die für das parallele Upgrade ausgeführt werden. Folgende Werte sind möglich: "Start", "Abbrechen"</param>
        <param name="lastActionTime">Zeitpunkt der letzten Aktion des Upgrades.</param>
        <summary>
            Initialisiert eine neue Instanz der RollingUpgradeRunningStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt; Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt; Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As Nullable(Of RollingUpgradeStatusCode)" />
      <MemberSignature Language="F#" Value="member this.Code : Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, Code, der den aktuellen Status des Upgrades angibt. Folgende Werte sind möglich: "RollingForward", "Abgebrochen", "Abgeschlossen", "Faulted"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt; LastAction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt; LastAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.LastAction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAction As Nullable(Of RollingUpgradeActionType)" />
      <MemberSignature Language="F#" Value="member this.LastAction : Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.LastAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.RollingUpgradeActionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die letzte Aktion, die für das parallele Upgrade durchgeführt. Folgende Werte sind möglich: "Start", "Abbrechen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastActionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastActionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.LastActionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastActionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.LastActionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastActionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die letzte Aktion Zeitpunkt des Upgrades.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit des Upgrades.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>