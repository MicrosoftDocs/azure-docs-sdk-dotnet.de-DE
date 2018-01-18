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
            <span data-ttu-id="50272-101">Informationen zu den aktuellen Ausführungsstatus des gesamten Upgrades.</span><span class="sxs-lookup"><span data-stu-id="50272-101">Information about the current running state of the overall upgrade.</span></span>
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
            <span data-ttu-id="50272-102">Initialisiert eine neue Instanz der RollingUpgradeRunningStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50272-102">Initializes a new instance of the RollingUpgradeRunningStatus class.</span></span>
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
        <param name="code"><span data-ttu-id="50272-103">Code, der angibt, des aktuellen Status des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="50272-103">Code indicating the current status of the upgrade.</span></span> <span data-ttu-id="50272-104">Folgende Werte sind möglich: "RollingForward", "Abgebrochen", "Abgeschlossen", "Faulted"</span><span class="sxs-lookup"><span data-stu-id="50272-104">Possible values include: 'RollingForward', 'Cancelled', 'Completed', 'Faulted'</span></span></param>
        <param name="startTime"><span data-ttu-id="50272-105">Die Startzeit des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="50272-105">Start time of the upgrade.</span></span></param>
        <param name="lastAction"><span data-ttu-id="50272-106">Die letzte Aktion, die für das parallele Upgrade ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="50272-106">The last action performed on the rolling upgrade.</span></span> <span data-ttu-id="50272-107">Folgende Werte sind möglich: "Start", "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="50272-107">Possible values include: 'Start', 'Cancel'</span></span></param>
        <param name="lastActionTime"><span data-ttu-id="50272-108">Zeitpunkt der letzten Aktion des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="50272-108">Last action time of the upgrade.</span></span></param>
        <summary>
            <span data-ttu-id="50272-109">Initialisiert eine neue Instanz der RollingUpgradeRunningStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50272-109">Initializes a new instance of the RollingUpgradeRunningStatus class.</span></span>
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
            <span data-ttu-id="50272-110">Ruft ab, Code, der den aktuellen Status des Upgrades angibt.</span><span class="sxs-lookup"><span data-stu-id="50272-110">Gets code indicating the current status of the upgrade.</span></span> <span data-ttu-id="50272-111">Folgende Werte sind möglich: "RollingForward", "Abgebrochen", "Abgeschlossen", "Faulted"</span><span class="sxs-lookup"><span data-stu-id="50272-111">Possible values include: 'RollingForward', 'Cancelled', 'Completed', 'Faulted'</span></span>
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
            <span data-ttu-id="50272-112">Ruft die letzte Aktion, die für das parallele Upgrade durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="50272-112">Gets the last action performed on the rolling upgrade.</span></span> <span data-ttu-id="50272-113">Folgende Werte sind möglich: "Start", "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="50272-113">Possible values include: 'Start', 'Cancel'</span></span>
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
            <span data-ttu-id="50272-114">Ruft die letzte Aktion Zeitpunkt des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="50272-114">Gets last action time of the upgrade.</span></span>
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
            <span data-ttu-id="50272-115">Ruft die Startzeit des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="50272-115">Gets start time of the upgrade.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>