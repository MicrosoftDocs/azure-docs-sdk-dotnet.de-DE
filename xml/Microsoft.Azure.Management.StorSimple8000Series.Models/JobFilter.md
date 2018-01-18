<Type Name="JobFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter">
  <TypeSignature Language="C#" Value="public class JobFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobFilter" />
  <TypeSignature Language="F#" Value="type JobFilter = class" />
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
            <span data-ttu-id="6694d-101">Der OData-Filter für Aufträge verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6694d-101">The OData filter to be used for jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6694d-102">Initialisiert eine neue Instanz der JobFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6694d-102">Initializes a new instance of the JobFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobFilter (string status = null, string jobType = null, Nullable&lt;DateTime&gt; startTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, string jobType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional jobType As String = null, Optional startTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter (status, jobType, startTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="6694d-103">Gibt den Status der Aufträge gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6694d-103">Specifies the status of the jobs to be filtered.</span></span> <span data-ttu-id="6694d-104">Für z. B. "Running", "Erfolg", "Fehler" oder "Abgebrochen".</span><span class="sxs-lookup"><span data-stu-id="6694d-104">For e.g., "Running", "Succeeded", "Failed" or "Canceled".</span></span>
            <span data-ttu-id="6694d-105">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6694d-105">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="jobType"><span data-ttu-id="6694d-106">Gibt den Typ der zu filternden Aufträge.</span><span class="sxs-lookup"><span data-stu-id="6694d-106">Specifies the type of the jobs to be filtered.</span></span> <span data-ttu-id="6694d-107">Für z. B. "'ScheduledBackup'", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs" oder "CreateCloudAppliance".</span><span class="sxs-lookup"><span data-stu-id="6694d-107">For e.g., "ScheduledBackup", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", or "CreateCloudAppliance".</span></span> <span data-ttu-id="6694d-108">Für diese Eigenschaft kann nur ' Gleichheitsoperator "verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6694d-108">Only 'Equality' operator can be used for this property.</span></span></param>
        <param name="startTime"><span data-ttu-id="6694d-109">Gibt die Startzeit der Aufträge gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6694d-109">Specifies the start time of the jobs to be filtered.</span></span>  <span data-ttu-id="6694d-110">Nur "größer als oder gleich" und "Kleiner als oder gleich" Operatoren für diese Eigenschaft unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="6694d-110">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="6694d-111">Initialisiert eine neue Instanz der JobFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6694d-111">Initializes a new instance of the JobFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public string JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As String" />
      <MemberSignature Language="F#" Value="member this.JobType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6694d-112">Ruft ab oder legt gibt den Typ der zu filternden Aufträge an.</span><span class="sxs-lookup"><span data-stu-id="6694d-112">Gets or sets specifies the type of the jobs to be filtered.</span></span> <span data-ttu-id="6694d-113">Für z. B. "'ScheduledBackup'", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs" oder "CreateCloudAppliance".</span><span class="sxs-lookup"><span data-stu-id="6694d-113">For e.g., "ScheduledBackup", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", or "CreateCloudAppliance".</span></span> <span data-ttu-id="6694d-114">Für diese Eigenschaft kann nur ' Gleichheitsoperator "verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6694d-114">Only 'Equality' operator can be used for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6694d-115">Ruft ab oder legt gibt die Startzeit der Aufträge gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6694d-115">Gets or sets specifies the start time of the jobs to be filtered.</span></span>
            <span data-ttu-id="6694d-116">Nur "größer als oder gleich" und "Kleiner als oder gleich" Operatoren für diese Eigenschaft unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="6694d-116">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.Status" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6694d-117">Ruft ab oder legt gibt den Status der Wiederherstellungsaufträge gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6694d-117">Gets or sets specifies the status of the jobs to be filtered.</span></span> <span data-ttu-id="6694d-118">Für z. B. "Running", "Erfolg", "Fehler" oder "Abgebrochen".</span><span class="sxs-lookup"><span data-stu-id="6694d-118">For e.g., "Running", "Succeeded", "Failed" or "Canceled".</span></span> <span data-ttu-id="6694d-119">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6694d-119">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>