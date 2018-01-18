<Type Name="ContainerHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class ContainerHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type ContainerHttpWebRequestFactory = class" />
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
            <span data-ttu-id="25dd4-101">Eine Factoryklasse zum Erstellen einer webanforderung zum Verwalten von Containern im Blob-Dienst.</span><span class="sxs-lookup"><span data-stu-id="25dd4-101">A factory class for constructing a web request to manage containers in the Blob service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><span data-ttu-id="25dd4-102">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-102">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="metadata"><span data-ttu-id="25dd4-103">Ein <see cref="T:System.Collections.Generic.Dictionary`2" /> Objekt, das die benutzerdefinierten Metadaten enthält.</span><span class="sxs-lookup"><span data-stu-id="25dd4-103">A <see cref="T:System.Collections.Generic.Dictionary`2" /> object containing the user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-104">Fügt benutzerdefinierte Metadaten für die Anforderung als ein oder mehrere Name-Wert-Paare hinzu.</span><span class="sxs-lookup"><span data-stu-id="25dd4-104">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><span data-ttu-id="25dd4-105">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-105">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="name"><span data-ttu-id="25dd4-106">Eine Zeichenfolge, enthält der Name der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="25dd4-106">A string containing the metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="25dd4-107">Eine Zeichenfolge, die den Metadatenwert enthält.</span><span class="sxs-lookup"><span data-stu-id="25dd4-107">A string containing the metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-108">Fügt benutzerdefinierte Metadaten für die Anforderung als ein einzelnes Name-Wert-Paar hinzu.</span><span class="sxs-lookup"><span data-stu-id="25dd4-108">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-109">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-109">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-110">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-110">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-111">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-111">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-112">Erstellt eine webanforderung an einen neuen Container erstellen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-112">Constructs a web request to create a new container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-113">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-113">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext,Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, operationContext, accessType)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-114">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-114">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-115">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-115">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-116">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-116">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="accessType"><span data-ttu-id="25dd4-117">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</span><span class="sxs-lookup"><span data-stu-id="25dd4-117">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and the level of access.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-118">Erstellt eine webanforderung an einen neuen Container erstellen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-118">Constructs a web request to create a new container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-119">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-119">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-120">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-120">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-121">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-121">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-122">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-122">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-123">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-123">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-124">Erstellt eine webanforderung an einen neuen Container erstellen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-124">Constructs a web request to create a new container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-125">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-125">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext,Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext, accessType)" />
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
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-126">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-126">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-127">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-127">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-128">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-128">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-129">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-129">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="accessType"><span data-ttu-id="25dd4-130">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</span><span class="sxs-lookup"><span data-stu-id="25dd4-130">An <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> object that specifies whether data in the container may be accessed publicly and the level of access.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-131">Erstellt eine webanforderung an einen neuen Container erstellen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-131">Constructs a web request to create a new container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-132">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-132">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-133">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-133">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-134">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-134">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-135">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-135">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-136">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-136">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-137">Erstellt eine webanforderung an den Container und alle darin enthaltenen Blobs zu löschen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-137">Constructs a web request to delete the container and all of the blobs within it.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-138">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-138">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="25dd4-139">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-139">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-140">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-140">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-141">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-141">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-142">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-142">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-143">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-144">Erstellt eine webanforderung an den Container und alle darin enthaltenen Blobs zu löschen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-144">Constructs a web request to delete the container and all of the blobs within it.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-145">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-145">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-146">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-146">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-147">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-147">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-148">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-148">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-149">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-149">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-150">Erstellt eine webanforderung, die ACL für einen Container zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-150">Constructs a web request to return the ACL for a container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-151">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-151">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="25dd4-152">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-152">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-153">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-153">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-154">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-154">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-155">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-155">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-156">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-156">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-157">Erstellt eine webanforderung, die ACL für einen Container zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-157">Constructs a web request to return the ACL for a container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-158">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-158">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-159">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-159">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-160">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-160">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-161">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-161">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-162">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-162">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-163">Generiert eine webanforderung an die benutzerdefinierten Metadaten für diesen Container zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-163">Generates a web request to return the user-defined metadata for this container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-164">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-164">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="25dd4-165">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-165">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-166">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-166">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-167">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-167">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-168">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-168">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-169">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-170">Generiert eine webanforderung an die benutzerdefinierten Metadaten für diesen Container zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-170">Generates a web request to return the user-defined metadata for this container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-171">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-171">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-172">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-172">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-173">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-173">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-174">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-174">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-175">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-175">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-176">Generiert eine webanforderung zum Zurückgeben von Eigenschaften und benutzerdefinierte Metadaten für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="25dd4-176">Generates a web request to return the properties and user-defined metadata for this container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-177">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-177">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="25dd4-178">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-178">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-179">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-179">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-180">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-180">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-181">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-181">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-182">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-182">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-183">Generiert eine webanforderung zum Zurückgeben von Eigenschaften und benutzerdefinierte Metadaten für diesen Container.</span><span class="sxs-lookup"><span data-stu-id="25dd4-183">Generates a web request to return the properties and user-defined metadata for this container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-184">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-184">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, operationContext)" />
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
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-185">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-185">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-186">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-186">An integer specifying the server timeout interval.</span></span></param>
        <param name="action"><span data-ttu-id="25dd4-187">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> -Enumerationswert, der angibt, der Lease auszuführende Aktion.</span><span class="sxs-lookup"><span data-stu-id="25dd4-187">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> enumeration value indicating the lease action to perform.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="25dd4-188">Eine Zeichenfolge, die Angabe der Lease-ID zum vorschlagen, die für das Ergebnis einer abrufen oder Ändern der Vorgang, oder <c>null</c> , wenn keine ID für den Abrufvorgang vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="25dd4-188">A string specifying the lease ID to propose for the result of an acquire or change operation, or <c>null</c> if no ID is proposed for an acquire operation.</span></span> <span data-ttu-id="25dd4-189">Dieser Parameter muss <c>null</c> für erneuern, Freigabe und Break-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="25dd4-189">This parameter should be <c>null</c> for renew, release, and break operations.</span></span></param>
        <param name="leaseDuration"><span data-ttu-id="25dd4-190">Die Leasedauer in Sekunden, erwerben Sie für Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="25dd4-190">The lease duration, in seconds, for acquire operations.</span></span>
            <span data-ttu-id="25dd4-191">Wenn dies-1 ist, wird eine unbegrenzte Dauer angegeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-191">If this is -1 then an infinite duration is specified.</span></span> <span data-ttu-id="25dd4-192">Dies dürfte <c>null</c> für verlängern, ändern, freigeben und Vorgänge unterbrochen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-192">This should be <c>null</c> for renew, change, release, and break operations.</span></span></param>
        <param name="leaseBreakPeriod"><span data-ttu-id="25dd4-193">Die Menge der Wartezeit in Sekunden, nach einem Vorgang unterbrechen, bevor die Lease unterbrochen wird, werden soll.</span><span class="sxs-lookup"><span data-stu-id="25dd4-193">The amount of time to wait, in seconds, after a break operation before the lease is broken.</span></span>
            <span data-ttu-id="25dd4-194">Ist dies <c>null</c> und dann die Standardzeit verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="25dd4-194">If this is <c>null</c> then the default time is used.</span></span> <span data-ttu-id="25dd4-195">Dies dürfte <c>null</c> für abrufen, erneuern, ändern und Freigeben von Vorgängen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-195">This should be <c>null</c> for acquire, renew, change, and release operations.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-196">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-196">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-197">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-197">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-198">Generiert eine webanforderung zum Abrufen, verlängern, ändern, freigeben oder Unterbrechen der Leases für den Container.</span><span class="sxs-lookup"><span data-stu-id="25dd4-198">Generates a web request to use to acquire, renew, change, release or break the lease for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-199">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-199">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-200">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-200">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-201">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-201">An integer specifying the server timeout interval.</span></span></param>
        <param name="action"><span data-ttu-id="25dd4-202">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> -Enumerationswert, der angibt, der Lease auszuführende Aktion.</span><span class="sxs-lookup"><span data-stu-id="25dd4-202">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> enumeration value indicating the lease action to perform.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="25dd4-203">Eine Zeichenfolge, die Angabe der Lease-ID zum vorschlagen, die für das Ergebnis einer abrufen oder Ändern der Vorgang, oder <c>null</c> , wenn keine ID für den Abrufvorgang vorgeschlagen wird.</span><span class="sxs-lookup"><span data-stu-id="25dd4-203">A string specifying the lease ID to propose for the result of an acquire or change operation, or <c>null</c> if no ID is proposed for an acquire operation.</span></span> <span data-ttu-id="25dd4-204">Dieser Parameter muss <c>null</c> für erneuern, Freigabe und Break-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="25dd4-204">This parameter should be <c>null</c> for renew, release, and break operations.</span></span></param>
        <param name="leaseDuration"><span data-ttu-id="25dd4-205">Die Leasedauer in Sekunden, erwerben Sie für Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="25dd4-205">The lease duration, in seconds, for acquire operations.</span></span>
            <span data-ttu-id="25dd4-206">Wenn dies-1 ist, wird eine unbegrenzte Dauer angegeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-206">If this is -1 then an infinite duration is specified.</span></span> <span data-ttu-id="25dd4-207">Dies dürfte <c>null</c> für verlängern, ändern, freigeben und Vorgänge unterbrochen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-207">This should be <c>null</c> for renew, change, release, and break operations.</span></span></param>
        <param name="leaseBreakPeriod"><span data-ttu-id="25dd4-208">Die Menge der Wartezeit in Sekunden, nach einem Vorgang unterbrechen, bevor die Lease unterbrochen wird, werden soll.</span><span class="sxs-lookup"><span data-stu-id="25dd4-208">The amount of time to wait, in seconds, after a break operation before the lease is broken.</span></span>
            <span data-ttu-id="25dd4-209">Ist dies <c>null</c> und dann die Standardzeit verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="25dd4-209">If this is <c>null</c> then the default time is used.</span></span> <span data-ttu-id="25dd4-210">Dies dürfte <c>null</c> für abrufen, erneuern, ändern und Freigeben von Vorgängen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-210">This should be <c>null</c> for acquire, renew, change, and release operations.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-211">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-211">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-212">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-212">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-213">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-213">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-214">Generiert eine webanforderung zum Abrufen, verlängern, ändern, freigeben oder Unterbrechen der Leases für den Container.</span><span class="sxs-lookup"><span data-stu-id="25dd4-214">Generates a web request to use to acquire, renew, change, release or break the lease for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-215">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-215">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-216">Ein <see cref="T:System.Uri" /> , den Blob-Dienstendpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-216">A <see cref="T:System.Uri" /> specifying the Blob service endpoint.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-217">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-217">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="25dd4-218">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-218">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="25dd4-219">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> -Enumerationswert ab, der angibt, ob die Metadaten des Containers mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="25dd4-219">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-220">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-220">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-221">Erstellt eine webanforderung an die in diesem Speicherkonto gibt eine Liste aller Container zurück.</span><span class="sxs-lookup"><span data-stu-id="25dd4-221">Constructs a web request to return a listing of all containers in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-222">Eine webanforderung für den angegebenen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="25dd4-222">A web request for the specified operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-223">Ein <see cref="T:System.Uri" /> , den Blob-Dienstendpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-223">A <see cref="T:System.Uri" /> specifying the Blob service endpoint.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-224">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-224">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="25dd4-225">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-225">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="25dd4-226">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> -Enumerationswert ab, der angibt, ob die Metadaten des Containers mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="25dd4-226">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> enumeration value that indicates whether to return container metadata with the listing.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-227">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-227">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-228">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-228">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-229">Erstellt eine webanforderung an die in diesem Speicherkonto gibt eine Liste aller Container zurück.</span><span class="sxs-lookup"><span data-stu-id="25dd4-229">Constructs a web request to return a listing of all containers in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-230">Eine webanforderung für den angegebenen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="25dd4-230">A web request for the specified operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListBlobs (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListBlobs(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListBlobs : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs (uri, timeout, listingContext, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-231">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-231">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-232">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-232">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="25dd4-233">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-233">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-234">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-234">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-235">Generiert eine webanforderung um eine Liste aller Blobs im Container zurück.</span><span class="sxs-lookup"><span data-stu-id="25dd4-235">Generates a web request to return a listing of all blobs in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-236">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-236">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListBlobs (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListBlobs(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListBlobs : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs (uri, timeout, listingContext, useVersionHeader, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-237">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-237">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-238">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-238">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="25dd4-239">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-239">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-240">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-240">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-241">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-241">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-242">Generiert eine webanforderung um eine Liste aller Blobs im Container zurück.</span><span class="sxs-lookup"><span data-stu-id="25dd4-242">Generates a web request to return a listing of all blobs in the container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-243">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-243">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl (uri, timeout, publicAccess, accessCondition, operationContext)" />
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
        <Parameter Name="publicAccess" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-244">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-244">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-245">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-245">An integer specifying the server timeout interval.</span></span></param>
        <param name="publicAccess"><span data-ttu-id="25dd4-246">Der Typ des öffentlichen Zugriff auf den Container zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-246">The type of public access to allow for the container.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-247">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-247">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-248">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-248">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-249">Erstellt eine webanforderung an die ACL für einen Container festgelegt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-249">Constructs a web request to set the ACL for a container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-250">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-250">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl (uri, timeout, publicAccess, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="publicAccess" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-251">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-251">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-252">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-252">An integer specifying the server timeout interval.</span></span></param>
        <param name="publicAccess"><span data-ttu-id="25dd4-253">Der Typ des öffentlichen Zugriff auf den Container zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-253">The type of public access to allow for the container.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-254">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-254">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-255">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-255">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-256">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-256">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-257">Erstellt eine webanforderung an die ACL für einen Container festgelegt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-257">Constructs a web request to set the ACL for a container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-258">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-258">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="25dd4-259">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-259">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-260">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-260">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-261">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-261">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-262">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-262">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-263">Generiert eine webanforderung benutzerdefinierte Metadaten für den Container festlegen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-263">Generates a web request to set user-defined metadata for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-264">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-264">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="25dd4-265">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-265">A <see cref="T:System.Uri" /> specifying the absolute URI to the container.</span></span></param>
        <param name="timeout"><span data-ttu-id="25dd4-266">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="25dd4-266">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="25dd4-267">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-267">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="25dd4-268">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="25dd4-268">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="25dd4-269">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-269">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="25dd4-270">Generiert eine webanforderung benutzerdefinierte Metadaten für den Container festlegen.</span><span class="sxs-lookup"><span data-stu-id="25dd4-270">Generates a web request to set user-defined metadata for the container.</span></span>
            </summary>
        <returns><span data-ttu-id="25dd4-271">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="25dd4-271">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>