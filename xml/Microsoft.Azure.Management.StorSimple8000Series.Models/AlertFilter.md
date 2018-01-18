<Type Name="AlertFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter">
  <TypeSignature Language="C#" Value="public class AlertFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AlertFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertFilter" />
  <TypeSignature Language="F#" Value="type AlertFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="799ef-101">Die OData-Filtern für die Warnung verwendet werden soll</span><span class="sxs-lookup"><span data-stu-id="799ef-101">The OData filters to be used for Alert</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="799ef-102">Initialisiert eine neue Instanz der AlertFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="799ef-102">Initializes a new instance of the AlertFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertFilter (Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; status = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; severity = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; sourceType = null, string sourceName = null, Nullable&lt;DateTime&gt; appearedOnTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; status, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; severity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; sourceType, string sourceName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; appearedOnTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.#ctor(System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As Nullable(Of AlertStatus) = null, Optional severity As Nullable(Of AlertSeverity) = null, Optional sourceType As Nullable(Of AlertSourceType) = null, Optional sourceName As String = null, Optional appearedOnTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter (status, severity, sourceType, sourceName, appearedOnTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt;" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt;" />
        <Parameter Name="sourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt;" />
        <Parameter Name="sourceName" Type="System.String" />
        <Parameter Name="appearedOnTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="799ef-103">Gibt den Status der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-103">Specifies the status of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-104">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-104">Only 'Equality' operator is supported for this property.</span></span>
            <span data-ttu-id="799ef-105">Folgende Werte sind möglich: "Aktiv", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="799ef-105">Possible values include: 'Active', 'Cleared'</span></span></param>
        <param name="severity"><span data-ttu-id="799ef-106">Gibt den Schweregrad der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-106">Specifies the severity of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-107">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-107">Only 'Equality' operator is supported for this property.</span></span>
            <span data-ttu-id="799ef-108">Folgende Werte sind möglich: "Information", "Warnung", "Kritisch"</span><span class="sxs-lookup"><span data-stu-id="799ef-108">Possible values include: 'Informational', 'Warning', 'Critical'</span></span></param>
        <param name="sourceType"><span data-ttu-id="799ef-109">Gibt den Quelltyp der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-109">Specifies the source type of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-110">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-110">Only 'Equality' operator is supported for this property.</span></span> <span data-ttu-id="799ef-111">Folgende Werte sind möglich: "Resource", "Gerät"</span><span class="sxs-lookup"><span data-stu-id="799ef-111">Possible values include: 'Resource', 'Device'</span></span></param>
        <param name="sourceName"><span data-ttu-id="799ef-112">Gibt den Quellnamen der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-112">Specifies the source name of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-113">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-113">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="appearedOnTime"><span data-ttu-id="799ef-114">Gibt die ist-Zeit (in UTC) der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-114">Specifies the appeared time (in UTC) of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-115">Nur "größer-als" und "kleiner-als" Operatoren für diese Eigenschaft unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="799ef-115">Only 'Greater-Than' and 'Lesser-Than' operators are supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="799ef-116">Initialisiert eine neue Instanz der AlertFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="799ef-116">Initializes a new instance of the AlertFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedOnTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AppearedOnTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AppearedOnTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.AppearedOnTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedOnTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AppearedOnTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.AppearedOnTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appearedOnTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="799ef-117">Ruft ab oder legt ihn fest gibt die ist-Zeit (in UTC) der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-117">Gets or sets specifies the appeared time (in UTC) of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-118">Nur "größer-als" und "kleiner-als" Operatoren für diese Eigenschaft unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="799ef-118">Only 'Greater-Than' and 'Lesser-Than' operators are supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; Severity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Severity" />
      <MemberSignature Language="VB.NET" Value="Public Property Severity As Nullable(Of AlertSeverity)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="799ef-119">Ruft ab oder legt gibt den Schweregrad der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-119">Gets or sets specifies the severity of the alerts to be filtered.</span></span>
            <span data-ttu-id="799ef-120">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-120">Only 'Equality' operator is supported for this property.</span></span> <span data-ttu-id="799ef-121">Folgende Werte sind möglich: "Information", "Warnung", "Kritisch"</span><span class="sxs-lookup"><span data-stu-id="799ef-121">Possible values include: 'Informational', 'Warning', 'Critical'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceName">
      <MemberSignature Language="C#" Value="public string SourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceName As String" />
      <MemberSignature Language="F#" Value="member this.SourceName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="799ef-122">Ruft ab oder legt gibt der Quellname der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-122">Gets or sets specifies the source name of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-123">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-123">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; SourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; SourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceType As Nullable(Of AlertSourceType)" />
      <MemberSignature Language="F#" Value="member this.SourceType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="799ef-124">Ruft ab oder legt gibt den Quelltyp der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-124">Gets or sets specifies the source type of the alerts to be filtered.</span></span> <span data-ttu-id="799ef-125">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-125">Only 'Equality' operator is supported for this property.</span></span>
            <span data-ttu-id="799ef-126">Folgende Werte sind möglich: "Resource", "Gerät"</span><span class="sxs-lookup"><span data-stu-id="799ef-126">Possible values include: 'Resource', 'Device'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of AlertStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="799ef-127">Ruft ab oder legt gibt den Status der Warnungen gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="799ef-127">Gets or sets specifies the status of the alerts to be filtered.</span></span>
            <span data-ttu-id="799ef-128">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="799ef-128">Only 'Equality' operator is supported for this property.</span></span> <span data-ttu-id="799ef-129">Folgende Werte sind möglich: "Aktiv", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="799ef-129">Possible values include: 'Active', 'Cleared'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>