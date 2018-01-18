<Type Name="JobProperties" FullName="Microsoft.Azure.Devices.JobProperties">
  <TypeSignature Language="C#" Value="public class JobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobProperties" />
  <TypeSignature Language="F#" Value="type JobProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cf180-101">Enthält die Eigenschaften eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="cf180-101">Contains properties of a Job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cf180-102">Standardkonstruktor, der ein leeres JobProperties-Objekt erstellt.</span><span class="sxs-lookup"><span data-stu-id="cf180-102">Default constructor that creates an empty JobProperties object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.EndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTimeUtc : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Devices.JobProperties.EndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="endTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-103">Vom System generiert.</span><span class="sxs-lookup"><span data-stu-id="cf180-103">System generated.</span></span>  <span data-ttu-id="cf180-104">Bei der Erstellung ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-104">Ignored at creation.</span></span>
            <span data-ttu-id="cf180-105">Stellt die Zeit, die Verarbeitung des Auftrags beendet.</span><span class="sxs-lookup"><span data-stu-id="cf180-105">Represents the time the job stopped processing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeKeysInExport">
      <MemberSignature Language="C#" Value="public bool ExcludeKeysInExport { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeKeysInExport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.ExcludeKeysInExport" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeKeysInExport As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeKeysInExport : bool with get, set" Usage="Microsoft.Azure.Devices.JobProperties.ExcludeKeysInExport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="excludeKeysInExport")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-106">für Exportaufträge optional. für andere Aufträge ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-106">Optional for export jobs; ignored for other jobs.</span></span>  <span data-ttu-id="cf180-107">Standardwert: false.</span><span class="sxs-lookup"><span data-stu-id="cf180-107">Default: false.</span></span>  <span data-ttu-id="cf180-108">Wenn "false" sind Autorisierung Schlüssel im Export-Ausgabe enthalten.</span><span class="sxs-lookup"><span data-stu-id="cf180-108">If false, authorization keys are included in export output.</span></span>  <span data-ttu-id="cf180-109">Schlüssel werden als null andernfalls exportiert.</span><span class="sxs-lookup"><span data-stu-id="cf180-109">Keys are exported as null otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public string FailureReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailureReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureReason As String" />
      <MemberSignature Language="F#" Value="member this.FailureReason : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="failureReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-110">System-Genereated.</span><span class="sxs-lookup"><span data-stu-id="cf180-110">System genereated.</span></span>  <span data-ttu-id="cf180-111">Bei der Erstellung ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-111">Ignored at creation.</span></span>
            <span data-ttu-id="cf180-112">Wenn Status == Fehler auftritt, wird dieser stellt eine Zeichenfolge mit dem Grund.</span><span class="sxs-lookup"><span data-stu-id="cf180-112">If status == failure, this represents a string containing the reason.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputBlobContainerUri">
      <MemberSignature Language="C#" Value="public string InputBlobContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputBlobContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.InputBlobContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property InputBlobContainerUri As String" />
      <MemberSignature Language="F#" Value="member this.InputBlobContainerUri : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.InputBlobContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="inputBlobContainerUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-113">Der URI mit SAS-Token zu einem blobcontainer, der, die zu synchronisierenden Registrierungsdaten enthält.</span><span class="sxs-lookup"><span data-stu-id="cf180-113">URI containing SAS token to a blob container that contains registry data to sync.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputBlobName">
      <MemberSignature Language="C#" Value="public string InputBlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputBlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.InputBlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property InputBlobName As String" />
      <MemberSignature Language="F#" Value="member this.InputBlobName : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.InputBlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="inputBlobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-114">Der Blob-Name beim Importieren aus der bereitgestellten Eingabe-Blob-Container verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="cf180-114">The blob name to be used when importing from the provided input blob container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-115">Vom System generiert.</span><span class="sxs-lookup"><span data-stu-id="cf180-115">System generated.</span></span>  <span data-ttu-id="cf180-116">Bei der Erstellung ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-116">Ignored at creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputBlobContainerUri">
      <MemberSignature Language="C#" Value="public string OutputBlobContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputBlobContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.OutputBlobContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputBlobContainerUri As String" />
      <MemberSignature Language="F#" Value="member this.OutputBlobContainerUri : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.OutputBlobContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputBlobContainerUri", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-117">Der URI, die SAS-Token zu einem blobcontainer enthält.</span><span class="sxs-lookup"><span data-stu-id="cf180-117">URI containing SAS token to a blob container.</span></span>  <span data-ttu-id="cf180-118">Dies wird verwendet, um den Status des Auftrags und die Ergebnisse ausgeben.</span><span class="sxs-lookup"><span data-stu-id="cf180-118">This is used to output the status of the job and the results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputBlobName">
      <MemberSignature Language="C#" Value="public string OutputBlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputBlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.OutputBlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputBlobName As String" />
      <MemberSignature Language="F#" Value="member this.OutputBlobName : string with get, set" Usage="Microsoft.Azure.Devices.JobProperties.OutputBlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="outputBlobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-119">Der Name des BLOBs, die in die bereitgestellte Ausgabe-Blob-Container erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="cf180-119">The name of the blob that will be created in the provided output blob container.</span></span>  <span data-ttu-id="cf180-120">Dieses Blob enthält Registrierungsinformationen für den IoT Hub exportierten Geräte.</span><span class="sxs-lookup"><span data-stu-id="cf180-120">This blob will contain the exported device registry information for the IoT Hub.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Progress">
      <MemberSignature Language="C#" Value="public int Progress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Progress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.Progress" />
      <MemberSignature Language="VB.NET" Value="Public Property Progress As Integer" />
      <MemberSignature Language="F#" Value="member this.Progress : int with get, set" Usage="Microsoft.Azure.Devices.JobProperties.Progress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="progress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-121">Vom System generiert.</span><span class="sxs-lookup"><span data-stu-id="cf180-121">System generated.</span></span>  <span data-ttu-id="cf180-122">Bei der Erstellung ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-122">Ignored at creation.</span></span>
            <span data-ttu-id="cf180-123">Gibt den Prozentsatz der Fertigstellung.</span><span class="sxs-lookup"><span data-stu-id="cf180-123">Represents the percentage of completion.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.StartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimeUtc : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Devices.JobProperties.StartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="startTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-124">Vom System generiert.</span><span class="sxs-lookup"><span data-stu-id="cf180-124">System generated.</span></span>  <span data-ttu-id="cf180-125">Bei der Erstellung ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-125">Ignored at creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As JobStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Devices.JobStatus with get, set" Usage="Microsoft.Azure.Devices.JobProperties.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-126">Vom System generiert.</span><span class="sxs-lookup"><span data-stu-id="cf180-126">System generated.</span></span>  <span data-ttu-id="cf180-127">Bei der Erstellung ignoriert.</span><span class="sxs-lookup"><span data-stu-id="cf180-127">Ignored at creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobProperties.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As JobType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Devices.JobType with get, set" Usage="Microsoft.Azure.Devices.JobProperties.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf180-128">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf180-128">Required.</span></span>
            <span data-ttu-id="cf180-129">Der Typ des auszuführenden Auftrag.</span><span class="sxs-lookup"><span data-stu-id="cf180-129">The type of job to execute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>