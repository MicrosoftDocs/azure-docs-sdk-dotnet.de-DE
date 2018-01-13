<Type Name="JobErrorDetails" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails">
  <TypeSignature Language="C#" Value="public class JobErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class JobErrorDetails" />
  <TypeSignature Language="F#" Value="type JobErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eeb74-101">Die Fehlerdetails für den Data Lake Analytics-Auftrag.</span><span class="sxs-lookup"><span data-stu-id="eeb74-101">The Data Lake Analytics job error details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-102">Initialisiert eine neue Instanz der JobErrorDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="eeb74-102">Initializes a new instance of the JobErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobErrorDetails (string description = null, string details = null, Nullable&lt;int&gt; endOffset = null, string errorId = null, string filePath = null, string helpLink = null, string internalDiagnostics = null, Nullable&lt;int&gt; lineNumber = null, string message = null, string resolution = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity = null, string source = null, Nullable&lt;int&gt; startOffset = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string description, string details, valuetype System.Nullable`1&lt;int32&gt; endOffset, string errorId, string filePath, string helpLink, string internalDiagnostics, valuetype System.Nullable`1&lt;int32&gt; lineNumber, string message, string resolution, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity, string source, valuetype System.Nullable`1&lt;int32&gt; startOffset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.#ctor(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError,System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional description As String = null, Optional details As String = null, Optional endOffset As Nullable(Of Integer) = null, Optional errorId As String = null, Optional filePath As String = null, Optional helpLink As String = null, Optional internalDiagnostics As String = null, Optional lineNumber As Nullable(Of Integer) = null, Optional message As String = null, Optional resolution As String = null, Optional innerError As JobInnerError = null, Optional severity As Nullable(Of SeverityTypes) = null, Optional source As String = null, Optional startOffset As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails : string * string * Nullable&lt;int&gt; * string * string * string * string * Nullable&lt;int&gt; * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails (description, details, endOffset, errorId, filePath, helpLink, internalDiagnostics, lineNumber, message, resolution, innerError, severity, source, startOffset)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="details" Type="System.String" />
        <Parameter Name="endOffset" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="helpLink" Type="System.String" />
        <Parameter Name="internalDiagnostics" Type="System.String" />
        <Parameter Name="lineNumber" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="resolution" Type="System.String" />
        <Parameter Name="innerError" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="startOffset" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="eeb74-103">die Beschreibung der Fehlermeldung</span><span class="sxs-lookup"><span data-stu-id="eeb74-103">the error message description</span></span></param>
        <param name="details"><span data-ttu-id="eeb74-104">die Details der Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="eeb74-104">the details of the error message.</span></span></param>
        <param name="endOffset"><span data-ttu-id="eeb74-105">Der Endoffset im Auftrag, in dem der Fehler gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="eeb74-105">the end offset in the job where the error was found.</span></span></param>
        <param name="errorId"><span data-ttu-id="eeb74-106">der spezifische Bezeichner für den Typ der Fehler im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="eeb74-106">the specific identifier for the type of error encountered in the job.</span></span></param>
        <param name="filePath"><span data-ttu-id="eeb74-107">der Pfad zu Fehlerdateien zusätzliche, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="eeb74-107">the path to any supplemental error files, if any.</span></span></param>
        <param name="helpLink"><span data-ttu-id="eeb74-108">der Link, um die MSDN oder Azure Hilfe für diese Art von Fehlern, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="eeb74-108">the link to MSDN or Azure help for this type of error, if any.</span></span></param>
        <param name="internalDiagnostics"><span data-ttu-id="eeb74-109">die interne Diagnose stapelüberwachung, wenn der Benutzer anfordern die Fehlerdetails des Auftrags über ausreichende Berechtigungen verfügt, die er abgerufen wird, wird andernfalls leer sein.</span><span class="sxs-lookup"><span data-stu-id="eeb74-109">the internal diagnostic stack trace if the user requesting the job error details has sufficient permissions it will be retrieved, otherwise it will be empty.</span></span></param>
        <param name="lineNumber"><span data-ttu-id="eeb74-110">die bestimmten Zeilennummer im Auftrag, in dem der Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="eeb74-110">the specific line number in the job where the error occured.</span></span></param>
        <param name="message"><span data-ttu-id="eeb74-111">die Benutzer-friendly-Fehlermeldung für den Fehler.</span><span class="sxs-lookup"><span data-stu-id="eeb74-111">the user friendly error message for the failure.</span></span></param>
        <param name="resolution"><span data-ttu-id="eeb74-112">die empfohlene Lösung für den Fehler, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="eeb74-112">the recommended resolution for the failure, if any.</span></span></param>
        <param name="innerError"><span data-ttu-id="eeb74-113">der interne Fehler dieser bestimmten Auftrag Fehlermeldung, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="eeb74-113">the inner error of this specific job error message, if any.</span></span></param>
        <param name="severity"><span data-ttu-id="eeb74-114">Der Schweregrad des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="eeb74-114">the severity level of the failure.</span></span> <span data-ttu-id="eeb74-115">Folgende Werte sind möglich: "Warnung", "Fehler", "Info", "SevereWarning", "Veraltet", "UserWarning"</span><span class="sxs-lookup"><span data-stu-id="eeb74-115">Possible values include: 'Warning', 'Error', 'Info', 'SevereWarning', 'Deprecated', 'UserWarning'</span></span></param>
        <param name="source"><span data-ttu-id="eeb74-116">die ultimative Quelle des Fehlers (normalerweise SYSTEM oder Benutzer).</span><span class="sxs-lookup"><span data-stu-id="eeb74-116">the ultimate source of the failure (usually either SYSTEM or USER).</span></span></param>
        <param name="startOffset"><span data-ttu-id="eeb74-117">der Anfangsoffset des Auftrags, wo der Fehler gefunden wurde</span><span class="sxs-lookup"><span data-stu-id="eeb74-117">the start offset in the job where the error was found</span></span></param>
        <summary>
            <span data-ttu-id="eeb74-118">Initialisiert eine neue Instanz der JobErrorDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="eeb74-118">Initializes a new instance of the JobErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-119">Ruft die Beschreibung der Fehlermeldung</span><span class="sxs-lookup"><span data-stu-id="eeb74-119">Gets the error message description</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-120">Ruft die Details der Fehlermeldung ab.</span><span class="sxs-lookup"><span data-stu-id="eeb74-120">Gets the details of the error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EndOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EndOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.EndOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EndOffset : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.EndOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-121">Ruft den Endoffset des Auftrags, wo der Fehler gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="eeb74-121">Gets the end offset in the job where the error was found.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.ErrorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-122">Ruft den bestimmten Bezeichner für den Typ der Fehler im Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="eeb74-122">Gets the specific identifier for the type of error encountered in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-123">Ruft den Pfad zu jeder Fehlerdateien zusätzliche ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="eeb74-123">Gets the path to any supplemental error files, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HelpLink">
      <MemberSignature Language="C#" Value="public string HelpLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HelpLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.HelpLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HelpLink As String" />
      <MemberSignature Language="F#" Value="member this.HelpLink : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.HelpLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="helpLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-124">Ruft den Link, um die MSDN oder Azure-Hilfe für diese Art von Fehlern, gegebenenfalls ab.</span><span class="sxs-lookup"><span data-stu-id="eeb74-124">Gets the link to MSDN or Azure help for this type of error, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InnerError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InnerError As JobInnerError" />
      <MemberSignature Language="F#" Value="member this.InnerError : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InnerError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innerError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-125">Ruft den inneren Fehler dieser Fehlermeldung bestimmten Auftrag ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="eeb74-125">Gets the inner error of this specific job error message, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDiagnostics">
      <MemberSignature Language="C#" Value="public string InternalDiagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InternalDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalDiagnostics As String" />
      <MemberSignature Language="F#" Value="member this.InternalDiagnostics : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InternalDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-126">Ruft die interne Diagnose stapelüberwachung ab, wenn der Benutzer anfordern, die Fehlerdetails des Auftrags verfügt über ausreichende Berechtigungen, die er abgerufen werden sollen, andernfalls er leer sein wird.</span><span class="sxs-lookup"><span data-stu-id="eeb74-126">Gets the internal diagnostic stack trace if the user requesting the job error details has sufficient permissions it will be retrieved, otherwise it will be empty.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LineNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LineNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LineNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.LineNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LineNumber As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LineNumber : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.LineNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lineNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-127">Ruft den bestimmten Zeilennummer im Auftrag, in dem der Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="eeb74-127">Gets the specific line number in the job where the error occured.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-128">Ruft die Benutzer benutzerfreundliche Fehlermeldung für den Fehler an.</span><span class="sxs-lookup"><span data-stu-id="eeb74-128">Gets the user friendly error message for the failure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resolution">
      <MemberSignature Language="C#" Value="public string Resolution { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resolution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Resolution" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resolution As String" />
      <MemberSignature Language="F#" Value="member this.Resolution : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Resolution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-129">Ruft ggf. die empfohlene Lösung des Fehlers ab.</span><span class="sxs-lookup"><span data-stu-id="eeb74-129">Gets the recommended resolution for the failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As Nullable(Of SeverityTypes)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-130">Ruft den Schweregrad des Fehlers ab.</span><span class="sxs-lookup"><span data-stu-id="eeb74-130">Gets the severity level of the failure.</span></span> <span data-ttu-id="eeb74-131">Folgende Werte sind möglich: "Warnung", "Fehler", "Info", "SevereWarning", "Veraltet", "UserWarning"</span><span class="sxs-lookup"><span data-stu-id="eeb74-131">Possible values include: 'Warning', 'Error', 'Info', 'SevereWarning', 'Deprecated', 'UserWarning'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-132">Ruft die ultimative Quelle des Fehlers ab (normalerweise SYSTEM oder Benutzer).</span><span class="sxs-lookup"><span data-stu-id="eeb74-132">Gets the ultimate source of the failure (usually either SYSTEM or USER).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StartOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StartOffset : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eeb74-133">Ruft den Anfangsoffset des Auftrags, wo der Fehler gefunden wurde</span><span class="sxs-lookup"><span data-stu-id="eeb74-133">Gets the start offset in the job where the error was found</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>