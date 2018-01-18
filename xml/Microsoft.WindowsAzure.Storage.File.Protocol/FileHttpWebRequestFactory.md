<Type Name="FileHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class FileHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FileHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type FileHttpWebRequestFactory = class" />
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
            <span data-ttu-id="d47cc-101">Eine Factoryklasse zum Erstellen von webanforderungen für Vorgänge für Dateien in der Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-101">A factory class for constructing web requests for operations on files in the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-102">Ein <see cref="T:System.Uri" /> den absoluten URI zur Datei angeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-103">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-103">An integer specifying the server timeout interval.</span></span></param>
        <param name="copyId"><span data-ttu-id="d47cc-104">Die ID-Zeichenfolge des Kopiervorgangs abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d47cc-104">The ID string of the copy operation to be aborted.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-105">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-105">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="d47cc-106">Nur die Lease-Bedingungen werden für diesen Vorgang unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-106">Only lease conditions are supported for this operation.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-107">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-107">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-108">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-109">Generiert eine webanforderung zum Abbrechen eines Kopiervorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-109">Generates a web request to abort a copy operation.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-110">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-110">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="d47cc-111">Der webanforderung.</span><span class="sxs-lookup"><span data-stu-id="d47cc-111">The web request.</span></span></param>
        <param name="metadata"><span data-ttu-id="d47cc-112">Die benutzerdefinierte Metadaten.</span><span class="sxs-lookup"><span data-stu-id="d47cc-112">The user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-113">Fügt benutzerdefinierte Metadaten für die Anforderung als ein oder mehrere Name-Wert-Paare hinzu.</span><span class="sxs-lookup"><span data-stu-id="d47cc-113">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="d47cc-114">Der webanforderung.</span><span class="sxs-lookup"><span data-stu-id="d47cc-114">The web request.</span></span></param>
        <param name="name"><span data-ttu-id="d47cc-115">Der Name der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="d47cc-115">The metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="d47cc-116">Der Wert der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="d47cc-116">The metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-117">Fügt benutzerdefinierte Metadaten für die Anforderung als ein einzelnes Name-Wert-Paar hinzu.</span><span class="sxs-lookup"><span data-stu-id="d47cc-117">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-118">Ein <see cref="T:System.Uri" /> den absoluten URI in die Zieldatei angeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-118">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-119">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-119">An integer specifying the server timeout interval.</span></span></param>
        <param name="source"><span data-ttu-id="d47cc-120">Ein <see cref="T:System.Uri" /> , den absoluten URI mit dem Quellobjekt, einschließlich aller erforderlichen Authentifizierungsinformationen-Parameter angibt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-120">A <see cref="T:System.Uri" /> specifying the absolute URI to the source object, including any necessary authentication parameters.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="d47cc-121">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung darstellt, die für das Quellobjekt in der Reihenfolge für die Anforderung zu fortfahren erfüllt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-121">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the source object in order for the request to proceed.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="d47cc-122">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung darstellt, die auf die Zieldatei, in der Reihenfolge für die Anforderung zu fortfahren erfüllt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-122">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the destination file in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-123">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-123">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-125">Generiert eine webanforderung von einem Blob oder die Datei in eine andere Datei kopieren.</span><span class="sxs-lookup"><span data-stu-id="d47cc-125">Generates a web request to copy from a blob or file to another file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-126">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-126">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileProperties properties, long fileSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileProperties properties, int64 fileSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileProperties,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileProperties * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Create (uri, timeout, properties, fileSize, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
        <Parameter Name="fileSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-127">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-127">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-128">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-128">The server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="d47cc-129">Die Eigenschaften für die Datei festlegen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-129">The properties to set for the file.</span></span></param>
        <param name="fileSize"><span data-ttu-id="d47cc-130">Die Größe der Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-130">The size of the file.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-131">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-131">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-132">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-132">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-133">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-133">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-134">Erstellt eine webanforderung zum Erstellen einer neuen Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-134">Constructs a web request to create a new file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-135">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-135">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-136">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-136">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-137">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-137">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-138">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-138">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-139">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-139">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-140">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-140">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-141">Erstellt eine webanforderung zum Löschen einer Datei an.</span><span class="sxs-lookup"><span data-stu-id="d47cc-141">Constructs a web request to delete a file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-142">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-142">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-143">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-143">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-144">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-144">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-145">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-145">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-146">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-146">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-147">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-147">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-148">Erstellt eine webanforderung zum Abrufen von Inhalt, Eigenschaften und Metadaten in der Datei an.</span><span class="sxs-lookup"><span data-stu-id="d47cc-148">Constructs a web request to get the file's content, properties, and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-149">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-149">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-150">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-150">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-151">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-151">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="d47cc-152">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="d47cc-152">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-153">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-153">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-154">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-154">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-155">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-155">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-156">Erstellt eine webanforderung zum Abrufen von Inhalt, Eigenschaften und Metadaten in der Datei an.</span><span class="sxs-lookup"><span data-stu-id="d47cc-156">Constructs a web request to get the file's content, properties, and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-157">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-157">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, offset, count, rangeContentMD5, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-158">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-158">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-159">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="d47cc-159">The server timeout interval, in seconds.</span></span></param>
        <param name="offset"><span data-ttu-id="d47cc-160">Der Offset in Bytes ab dem Inhalt zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="d47cc-160">The byte offset at which to begin returning content.</span></span></param>
        <param name="count"><span data-ttu-id="d47cc-161">Die Anzahl der Bytes, die zurückgegeben oder null, wenn alle Bytes bis zum Ende der Datei zurück.</span><span class="sxs-lookup"><span data-stu-id="d47cc-161">The number of bytes to return, or null to return all bytes through the end of the file.</span></span></param>
        <param name="rangeContentMD5"><span data-ttu-id="d47cc-162">Wenn auf festgelegt <c>"true"</c>, MD5-Header für den angegebenen Bereich anfordern.</span><span class="sxs-lookup"><span data-stu-id="d47cc-162">If set to <c>true</c>, request an MD5 header for the specified range.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-163">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-163">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-164">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-164">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-165">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-165">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-166">Erstellt eine webanforderung, die einen angegebenen Bereich der Dateiinhalt zusammen mit seinen Eigenschaften und Metadaten zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-166">Constructs a web request to return a specified range of the file's content, together with its properties and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-167">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-167">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, offset, count, rangeContentMD5, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-168">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-168">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-169">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="d47cc-169">The server timeout interval, in seconds.</span></span></param>
        <param name="offset"><span data-ttu-id="d47cc-170">Der Offset in Bytes ab dem Inhalt zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="d47cc-170">The byte offset at which to begin returning content.</span></span></param>
        <param name="count"><span data-ttu-id="d47cc-171">Die Anzahl der Bytes, die zurückgegeben oder null, wenn alle Bytes bis zum Ende der Datei zurück.</span><span class="sxs-lookup"><span data-stu-id="d47cc-171">The number of bytes to return, or null to return all bytes through the end of the file.</span></span></param>
        <param name="rangeContentMD5"><span data-ttu-id="d47cc-172">Wenn auf festgelegt <c>"true"</c>, MD5-Header für den angegebenen Bereich anfordern.</span><span class="sxs-lookup"><span data-stu-id="d47cc-172">If set to <c>true</c>, request an MD5 header for the specified range.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="d47cc-173">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="d47cc-173">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-174">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-174">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-175">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-175">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-176">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-176">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-177">Erstellt eine webanforderung, die einen angegebenen Bereich der Dateiinhalt zusammen mit seinen Eigenschaften und Metadaten zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-177">Constructs a web request to return a specified range of the file's content, together with its properties and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-178">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-178">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-179">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-179">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-180">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-180">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-181">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-181">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-182">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-182">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-183">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-183">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-184">Erstellt eine webanforderung an die benutzerdefinierten Metadaten für die Datei zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-184">Constructs a web request to return the user-defined metadata for the file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-185">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-185">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-186">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-186">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-187">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-187">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="d47cc-188">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="d47cc-188">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-189">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-189">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-190">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-190">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-191">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-191">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-192">Erstellt eine webanforderung an die benutzerdefinierten Metadaten für die Datei zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-192">Constructs a web request to return the user-defined metadata for the file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-193">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-193">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-194">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-194">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-195">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-195">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-196">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-196">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-197">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-197">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-198">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-198">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-199">Erstellt eine webanforderung, die Dateisystemeigenschaften zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-199">Constructs a web request to return the file's system properties.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-200">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-200">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-201">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-201">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-202">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-202">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="d47cc-203">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="d47cc-203">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-204">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-204">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-205">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-205">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-206">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-206">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-207">Erstellt eine webanforderung, die Dateisystemeigenschaften zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-207">Constructs a web request to return the file's system properties.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-208">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-208">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-209">Ein <see cref="T:System.Uri" /> der Dateidienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-209">A <see cref="T:System.Uri" /> specifying the File service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="d47cc-210">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-210">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-211">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="d47cc-211">The server timeout interval, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-212">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-212">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-213">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-213">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-214">Erstellt eine webanforderung zum Abrufen der Eigenschaften des dateidiensts.</span><span class="sxs-lookup"><span data-stu-id="d47cc-214">Creates a web request to get the properties of the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-215">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-215">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges (uri, timeout, offset, count, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-216">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-216">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-217">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-217">The server timeout interval.</span></span></param>
        <param name="offset"><span data-ttu-id="d47cc-218">Der Startoffset des Datenbereichs, über die Liste Datei Seitenbereiche (in Bytes).</span><span class="sxs-lookup"><span data-stu-id="d47cc-218">The starting offset of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="count"><span data-ttu-id="d47cc-219">Die Länge des Datenbereichs, über die Liste Datei Seitenbereiche (in Bytes).</span><span class="sxs-lookup"><span data-stu-id="d47cc-219">The length of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-220">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-220">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-221">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-221">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-222">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-222">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-223">Erstellt eine webanforderung an die Liste der gültigen Bereiche für eine Datei zurück.</span><span class="sxs-lookup"><span data-stu-id="d47cc-223">Constructs a web request to return the list of valid ranges for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-224">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-224">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges (uri, timeout, offset, count, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-225">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-225">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-226">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-226">The server timeout interval.</span></span></param>
        <param name="offset"><span data-ttu-id="d47cc-227">Der Startoffset des Datenbereichs, über die Liste Datei Seitenbereiche (in Bytes).</span><span class="sxs-lookup"><span data-stu-id="d47cc-227">The starting offset of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="count"><span data-ttu-id="d47cc-228">Die Länge des Datenbereichs, über die Liste Datei Seitenbereiche (in Bytes).</span><span class="sxs-lookup"><span data-stu-id="d47cc-228">The length of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="d47cc-229">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="d47cc-229">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-230">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-230">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-231">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-231">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-232">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-232">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-233">Erstellt eine webanforderung an die Liste der gültigen Bereiche für eine Datei zurück.</span><span class="sxs-lookup"><span data-stu-id="d47cc-233">Constructs a web request to return the list of valid ranges for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-234">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-234">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutRange">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutRange (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileRange fileRange, Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite fileRangeWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutRange(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileRange fileRange, valuetype Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite fileRangeWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.PutRange(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileRange,Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutRange : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileRange * Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.PutRange (uri, timeout, fileRange, fileRangeWrite, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="fileRange" Type="Microsoft.WindowsAzure.Storage.File.FileRange" />
        <Parameter Name="fileRangeWrite" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-235">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-235">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-236">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-236">The server timeout interval.</span></span></param>
        <param name="fileRange"><span data-ttu-id="d47cc-237">Anfang und Ende-Offsets.</span><span class="sxs-lookup"><span data-stu-id="d47cc-237">The beginning and ending offsets.</span></span></param>
        <param name="fileRangeWrite"><span data-ttu-id="d47cc-238">Die Aktion, die beschreibt, ob es in eine Datei schreiben oder das Löschen einer Gruppe von Bereichen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-238">Action describing whether we are writing to a file or clearing a set of ranges.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-239">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-239">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-240">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-240">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-241">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-241">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-242">Erstellt eine webanforderung zum Schreiben oder einen Bereich von Seiten in einer Datei zu löschen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-242">Constructs a web request to write or clear a range of pages in a file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-243">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-243">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newFileSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newFileSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Resize (uri, timeout, newFileSize, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="newFileSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-244">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-244">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-245">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-245">The server timeout interval.</span></span></param>
        <param name="newFileSize"><span data-ttu-id="d47cc-246">Die neue Dateigröße.</span><span class="sxs-lookup"><span data-stu-id="d47cc-246">The new file size.</span></span> <span data-ttu-id="d47cc-247">Legen Sie diesen Parameter auf <c>null</c> vorhandenen Dateigröße beibehalten.</span><span class="sxs-lookup"><span data-stu-id="d47cc-247">Set this parameter to <c>null</c> to keep the existing file size.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-248">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-248">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-249">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-249">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-250">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-250">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-251">Erstellt eine webanforderung an die Größe einer Datei ändern.</span><span class="sxs-lookup"><span data-stu-id="d47cc-251">Constructs a web request to resize a file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-252">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-252">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-253">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-253">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-254">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-254">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-255">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-255">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-256">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-256">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-257">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-257">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-258">Erstellt eine webanforderung fest benutzerdefinierten Metadaten für die Datei an.</span><span class="sxs-lookup"><span data-stu-id="d47cc-258">Constructs a web request to set user-defined metadata for the file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-259">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-259">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-260">Der absolute URI zur Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-260">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-261">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="d47cc-261">The server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="d47cc-262">Die Eigenschaften der Datei.</span><span class="sxs-lookup"><span data-stu-id="d47cc-262">The file's properties.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="d47cc-263">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="d47cc-263">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-264">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-264">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-265">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d47cc-265">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-266">Erstellt eine webanforderung, Systemeigenschaften für eine Datei festzulegen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-266">Constructs a web request to set system properties for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-267">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-267">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d47cc-268">Ein <see cref="T:System.Uri" /> der Dateidienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="d47cc-268">A <see cref="T:System.Uri" /> specifying the File service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="d47cc-269">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="d47cc-269">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d47cc-270">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="d47cc-270">The server timeout interval, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d47cc-271">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="d47cc-271">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d47cc-272">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-272">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-273">Erstellt eine webanforderung zum Festlegen der Eigenschaften des dateidiensts.</span><span class="sxs-lookup"><span data-stu-id="d47cc-273">Creates a web request to set the properties of the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="d47cc-274">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-274">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As FileServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d47cc-275">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d47cc-275">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="outputStream"><span data-ttu-id="d47cc-276">Die <see cref="T:System.IO.Stream" /> auf das sind die formatierte Eigenschaften geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="d47cc-276">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="d47cc-277">Schreibt dateidiensteigenschaften in einen Stream, in XML formatiert.</span><span class="sxs-lookup"><span data-stu-id="d47cc-277">Writes File service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>