<Type Name="MonitoringSummary" FullName="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary">
  <TypeSignature Language="C#" Value="public class MonitoringSummary" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MonitoringSummary extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary" />
  <TypeSignature Language="VB.NET" Value="Public Class MonitoringSummary" />
  <TypeSignature Language="F#" Value="type MonitoringSummary = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e20b-101">Zusammenfassung der Replikation Überwachungsdaten für diesen Tresor.</span><span class="sxs-lookup"><span data-stu-id="1e20b-101">Summary of the replication monitoring data for this vault.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoringSummary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-102">Initialisiert eine neue Instanz der MonitoringSummary-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e20b-102">Initializes a new instance of the MonitoringSummary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoringSummary (Nullable&lt;int&gt; unHealthyVmCount = null, Nullable&lt;int&gt; unHealthyProviderCount = null, Nullable&lt;int&gt; eventsCount = null, Nullable&lt;int&gt; deprecatedProviderCount = null, Nullable&lt;int&gt; supportedProviderCount = null, Nullable&lt;int&gt; unsupportedProviderCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; unHealthyVmCount, valuetype System.Nullable`1&lt;int32&gt; unHealthyProviderCount, valuetype System.Nullable`1&lt;int32&gt; eventsCount, valuetype System.Nullable`1&lt;int32&gt; deprecatedProviderCount, valuetype System.Nullable`1&lt;int32&gt; supportedProviderCount, valuetype System.Nullable`1&lt;int32&gt; unsupportedProviderCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional unHealthyVmCount As Nullable(Of Integer) = null, Optional unHealthyProviderCount As Nullable(Of Integer) = null, Optional eventsCount As Nullable(Of Integer) = null, Optional deprecatedProviderCount As Nullable(Of Integer) = null, Optional supportedProviderCount As Nullable(Of Integer) = null, Optional unsupportedProviderCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary (unHealthyVmCount, unHealthyProviderCount, eventsCount, deprecatedProviderCount, supportedProviderCount, unsupportedProviderCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="unHealthyVmCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="unHealthyProviderCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eventsCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="deprecatedProviderCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="supportedProviderCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="unsupportedProviderCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="unHealthyVmCount"><span data-ttu-id="1e20b-103">Die Anzahl der VMs "fehlerhaft".</span><span class="sxs-lookup"><span data-stu-id="1e20b-103">Count of unhealthy VMs.</span></span></param>
        <param name="unHealthyProviderCount"><span data-ttu-id="1e20b-104">Die Anzahl der fehlerhaften Replikations-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-104">Count of unhealthy replication providers.</span></span></param>
        <param name="eventsCount"><span data-ttu-id="1e20b-105">Die Anzahl der alle kritischen Warnungen.</span><span class="sxs-lookup"><span data-stu-id="1e20b-105">Count of all critical warnings.</span></span></param>
        <param name="deprecatedProviderCount"><span data-ttu-id="1e20b-106">Die Anzahl der alle veralteten Recovery Provider.</span><span class="sxs-lookup"><span data-stu-id="1e20b-106">Count of all deprecated recovery service providers.</span></span></param>
        <param name="supportedProviderCount"><span data-ttu-id="1e20b-107">Die Anzahl der die unterstützte Wiederherstellung-Dienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-107">Count of all the supported recovery service providers.</span></span></param>
        <param name="unsupportedProviderCount"><span data-ttu-id="1e20b-108">Anzahl der nicht unterstützte Wiederherstellung-Dienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-108">Count of all the unsupported recovery service providers.</span></span></param>
        <summary>
            <span data-ttu-id="1e20b-109">Initialisiert eine neue Instanz der MonitoringSummary-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e20b-109">Initializes a new instance of the MonitoringSummary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeprecatedProviderCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DeprecatedProviderCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DeprecatedProviderCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.DeprecatedProviderCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DeprecatedProviderCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DeprecatedProviderCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.DeprecatedProviderCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deprecatedProviderCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-110">Abrufen oder Festlegen der Anzahl der Wiederherstellung für alle veralteten Dienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-110">Gets or sets count of all deprecated recovery service providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.EventsCount" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.EventsCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventsCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-111">Abrufen oder Festlegen der Anzahl der alle kritischen Warnungen.</span><span class="sxs-lookup"><span data-stu-id="1e20b-111">Gets or sets count of all critical warnings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedProviderCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SupportedProviderCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SupportedProviderCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.SupportedProviderCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedProviderCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SupportedProviderCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.SupportedProviderCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedProviderCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-112">Abrufen oder Festlegen der Anzahl der unterstützten Wiederherstellung Dienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-112">Gets or sets count of all the supported recovery service providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnHealthyProviderCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UnHealthyProviderCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UnHealthyProviderCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.UnHealthyProviderCount" />
      <MemberSignature Language="VB.NET" Value="Public Property UnHealthyProviderCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UnHealthyProviderCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.UnHealthyProviderCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unHealthyProviderCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-113">Ruft ab oder legt die Anzahl der fehlerhaften Replikations-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-113">Gets or sets count of unhealthy replication providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnHealthyVmCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UnHealthyVmCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UnHealthyVmCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.UnHealthyVmCount" />
      <MemberSignature Language="VB.NET" Value="Public Property UnHealthyVmCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UnHealthyVmCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.UnHealthyVmCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unHealthyVmCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-114">Ruft ab, oder setzt die Anzahl der fehlerhaften virtuellen Computern.</span><span class="sxs-lookup"><span data-stu-id="1e20b-114">Gets or sets count of unhealthy VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnsupportedProviderCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UnsupportedProviderCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UnsupportedProviderCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.UnsupportedProviderCount" />
      <MemberSignature Language="VB.NET" Value="Public Property UnsupportedProviderCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UnsupportedProviderCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary.UnsupportedProviderCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unsupportedProviderCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e20b-115">Ruft ab oder legt die Anzahl der nicht unterstützte Wiederherstellung Dienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e20b-115">Gets or sets count of all the unsupported recovery service providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>