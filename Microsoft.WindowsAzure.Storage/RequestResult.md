<Type Name="RequestResult" FullName="Microsoft.WindowsAzure.Storage.RequestResult">
  <TypeSignature Language="C#" Value="public sealed class RequestResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit RequestResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RequestResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestResult" />
  <TypeSignature Language="F#" Value="type RequestResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6e964-101">Stellt das Ergebnis einer physischen Anforderung dar.</span><span class="sxs-lookup"><span data-stu-id="6e964-101">Represents the result of a physical request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentMd5">
      <MemberSignature Language="C#" Value="public string ContentMd5 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentMd5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.ContentMd5" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentMd5 As String" />
      <MemberSignature Language="F#" Value="member this.ContentMd5 : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.ContentMd5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-102">Ruft den Content-MD5-Wert für die Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-102">Gets the content-MD5 value for the request.</span></span> 
            </summary>
        <value><span data-ttu-id="6e964-103">Der Content-MD5-Wert für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6e964-103">The content-MD5 value for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EgressBytes">
      <MemberSignature Language="C#" Value="public long EgressBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EgressBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.EgressBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property EgressBytes As Long" />
      <MemberSignature Language="F#" Value="member this.EgressBytes : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.EgressBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>        
            <span data-ttu-id="6e964-104">Die Anzahl der Bytes, die geschrieben wurden dem Anforderungstext für eine bestimmte Anforderung</span><span class="sxs-lookup"><span data-stu-id="6e964-104">The number of bytes written to the request body for a given request</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime" Usage="Microsoft.WindowsAzure.Storage.RequestResult.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-105">Ruft die Endzeit des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-105">Gets the end time of the operation.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-106">Ein <see cref="T:System.DateTime" /> Wert, der angibt, der Endzeit des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6e964-106">A <see cref="T:System.DateTime" /> value indicating the end time of the operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-107">Ruft den ETag-Wert, der die Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-107">Gets the ETag value of the request.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-108">Der ETag-Wert, der die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6e964-108">The ETag value of the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-109">Ruft ab oder legt die Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="6e964-109">Gets or sets the exception.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-110">Ein <see cref="T:System.Exception" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6e964-110">An <see cref="T:System.Exception" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedErrorInformation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ExtendedErrorInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ExtendedErrorInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.ExtendedErrorInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExtendedErrorInformation As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="member this.ExtendedErrorInformation : Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.WindowsAzure.Storage.RequestResult.ExtendedErrorInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-111">Ruft die erweiterten Fehlerinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-111">Gets the extended error information.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-112">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6e964-112">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public int HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : int with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-113">Ruft ab oder legt den HTTP-Statuscode für die Anforderung fest.</span><span class="sxs-lookup"><span data-stu-id="6e964-113">Gets or sets the HTTP status code for the request.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-114">Der HTTP-Statuscode für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6e964-114">The HTTP status code for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusMessage">
      <MemberSignature Language="C#" Value="public string HttpStatusMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpStatusMessage As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatusMessage : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.HttpStatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-115">Ruft die HTTP-Statusnachricht für die Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-115">Gets the HTTP status message for the request.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-116">Die HTTP-Statusnachricht für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6e964-116">The HTTP status message for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IngressBytes">
      <MemberSignature Language="C#" Value="public long IngressBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IngressBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.IngressBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property IngressBytes As Long" />
      <MemberSignature Language="F#" Value="member this.IngressBytes : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.RequestResult.IngressBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-117">Die Anzahl der gelesenen Bytes aus dem Antworttext für die angegebene Anforderung</span><span class="sxs-lookup"><span data-stu-id="6e964-117">The number of bytes read from the response body for the given request</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRequestServerEncrypted">
      <MemberSignature Language="C#" Value="public bool IsRequestServerEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRequestServerEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.IsRequestServerEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRequestServerEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRequestServerEncrypted : bool" Usage="Microsoft.WindowsAzure.Storage.RequestResult.IsRequestServerEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-118">Ruft ab, und zwar unabhängig davon, ob die Daten für einen Schreibvorgang serverseitige verschlüsselt ist.</span><span class="sxs-lookup"><span data-stu-id="6e964-118">Gets whether or not the data for a write operation is encrypted server-side.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadXml">
      <MemberSignature Language="C#" Value="public void ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReadXml (reader As XmlReader)" />
      <MemberSignature Language="F#" Value="member this.ReadXml : System.Xml.XmlReader -&gt; unit" Usage="requestResult.ReadXml reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="6e964-119">Die <see cref="T:System.Xml.XmlReader" /> stream, aus dem "requestresult" deserialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6e964-119">The <see cref="T:System.Xml.XmlReader" /> stream from which the RequestResult is deserialized.</span></span></param>
        <summary>
            <span data-ttu-id="6e964-120">Generiert ein serialisierbares "requestresult" aus seiner XML-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="6e964-120">Generates a serializable RequestResult from its XML representation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestDate">
      <MemberSignature Language="C#" Value="public string RequestDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.RequestDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestDate As String" />
      <MemberSignature Language="F#" Value="member this.RequestDate : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.RequestDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-121">Ruft das Anforderungsdatum ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-121">Gets the request date.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-122">Das Anforderungsdatum.</span><span class="sxs-lookup"><span data-stu-id="6e964-122">The request date.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestID">
      <MemberSignature Language="C#" Value="public string ServiceRequestID { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceRequestID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.ServiceRequestID" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceRequestID As String" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestID : string" Usage="Microsoft.WindowsAzure.Storage.RequestResult.ServiceRequestID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-123">Ruft die dienstanforderungs-ID für diese Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-123">Gets the service request ID for this request.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-124">Die dienstanforderungs-ID für diese Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6e964-124">The service request ID for this request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.WindowsAzure.Storage.RequestResult.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-125">Ruft die Startzeit des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="6e964-125">Gets the start time of the operation.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-126">Ein <see cref="T:System.DateTime" /> Wert, der angibt, der Startzeit des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6e964-126">A <see cref="T:System.DateTime" /> value indicating the start time of the operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestResult.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetLocation As StorageLocation" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Microsoft.WindowsAzure.Storage.StorageLocation" Usage="Microsoft.WindowsAzure.Storage.RequestResult.TargetLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e964-127">Ruft den Speicherort, an den die Anforderung gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="6e964-127">Gets the location to which the request was sent.</span></span>
            </summary>
        <value><span data-ttu-id="6e964-128">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="6e964-128">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateFromExceptionMessage">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.RequestResult TranslateFromExceptionMessage (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.RequestResult TranslateFromExceptionMessage(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.TranslateFromExceptionMessage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateFromExceptionMessage (message As String) As RequestResult" />
      <MemberSignature Language="F#" Value="static member TranslateFromExceptionMessage : string -&gt; Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.RequestResult.TranslateFromExceptionMessage message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This should be available only in Microsoft.WindowsAzure.Storage.WinMD and not in Microsoft.WindowsAzure.Storage.dll. Please use ReadXML to deserialize RequestResult when Microsoft.WindowsAzure.Storage.dll is used.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6e964-129">Das zu übersetzende Nachricht.</span><span class="sxs-lookup"><span data-stu-id="6e964-129">The message to translate.</span></span></param>
        <summary>
            <span data-ttu-id="6e964-130">Übersetzt die angegebene Nachricht in eine <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="6e964-130">Translates the specified message into a <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> object.</span></span>
            </summary>
        <returns><span data-ttu-id="6e964-131">Der übersetzte <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />.</span><span class="sxs-lookup"><span data-stu-id="6e964-131">The translated <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteXml">
      <MemberSignature Language="C#" Value="public void WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestResult.WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub WriteXml (writer As XmlWriter)" />
      <MemberSignature Language="F#" Value="member this.WriteXml : System.Xml.XmlWriter -&gt; unit" Usage="requestResult.WriteXml writer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="6e964-132">Die <see cref="T:System.Xml.XmlWriter" /> stream, in dem "requestresult" serialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6e964-132">The <see cref="T:System.Xml.XmlWriter" /> stream to which the RequestResult is serialized.</span></span></param>
        <summary>
            <span data-ttu-id="6e964-133">Konvertiert ein serialisierbares "requestresult" in seine XML-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="6e964-133">Converts a serializable RequestResult into its XML representation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>