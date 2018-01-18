<Type Name="DirectoryHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class DirectoryHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DirectoryHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type DirectoryHttpWebRequestFactory = class" />
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
            <span data-ttu-id="907ca-101">Eine Factoryklasse zum Erstellen von webanforderungen für Vorgänge für Verzeichnisse in den Dateidienst.</span><span class="sxs-lookup"><span data-stu-id="907ca-101">A factory class for constructing web requests for operations on directories in the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><span data-ttu-id="907ca-102">Der webanforderung.</span><span class="sxs-lookup"><span data-stu-id="907ca-102">The web request.</span></span></param>
        <param name="metadata"><span data-ttu-id="907ca-103">Die benutzerdefinierte Metadaten.</span><span class="sxs-lookup"><span data-stu-id="907ca-103">The user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-104">Fügt benutzerdefinierte Metadaten für die Anforderung als ein oder mehrere Name-Wert-Paare hinzu.</span><span class="sxs-lookup"><span data-stu-id="907ca-104">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><span data-ttu-id="907ca-105">Der webanforderung.</span><span class="sxs-lookup"><span data-stu-id="907ca-105">The web request.</span></span></param>
        <param name="name"><span data-ttu-id="907ca-106">Der Name der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="907ca-106">The metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="907ca-107">Der Wert der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="907ca-107">The metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-108">Fügt benutzerdefinierte Metadaten für die Anforderung als ein einzelnes Name-Wert-Paar hinzu.</span><span class="sxs-lookup"><span data-stu-id="907ca-108">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-109">Der absolute URI zum Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-109">The absolute URI to the directory.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-110">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-110">The server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-111">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="907ca-111">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-112">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-112">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-113">Erstellt eine webanforderung zum Erstellen eines neuen Verzeichnisses.</span><span class="sxs-lookup"><span data-stu-id="907ca-113">Constructs a web request to create a new directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-114">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="907ca-114">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-115">Der absolute URI zum Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-115">The absolute URI to the directory.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-116">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-116">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="907ca-117">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="907ca-117">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-118">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="907ca-118">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-119">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-119">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-120">Erstellt eine webanforderung zum Löschen des Verzeichnisses und aller darin enthaltenen Dateien.</span><span class="sxs-lookup"><span data-stu-id="907ca-120">Constructs a web request to delete the directory and all of the files within it.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-121">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="907ca-121">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-122">Der absolute URI zum Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-122">The absolute URI to the directory.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-123">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-123">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="907ca-124">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="907ca-124">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-125">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="907ca-125">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-126">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-126">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-127">Generiert eine webanforderung, um die benutzerdefinierten Metadaten für dieses Verzeichnis zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="907ca-127">Generates a web request to return the user-defined metadata for this directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-128">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="907ca-128">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-129">Der absolute URI zum Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-129">The absolute URI to the directory.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-130">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-130">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="907ca-131">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="907ca-131">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="907ca-132">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="907ca-132">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-133">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="907ca-133">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-134">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-134">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-135">Generiert eine webanforderung, um die benutzerdefinierten Metadaten für dieses Verzeichnis zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="907ca-135">Generates a web request to return the user-defined metadata for this directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-136">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="907ca-136">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-137">Der absolute URI zum Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-137">The absolute URI to the directory.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-138">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-138">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="907ca-139">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="907ca-139">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-140">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="907ca-140">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-141">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-141">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-142">Generiert eine webanforderung zum Zurückgeben von Eigenschaften und benutzerdefinierte Metadaten für dieses Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-142">Generates a web request to return the properties and user-defined metadata for this directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-143">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="907ca-143">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-144">Der absolute URI zum Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-144">The absolute URI to the directory.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-145">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-145">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="907ca-146">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="907ca-146">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="907ca-147">Die Bedingung für den Zugriff auf die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="907ca-147">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-148">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="907ca-148">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-149">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-149">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-150">Generiert eine webanforderung zum Zurückgeben von Eigenschaften und benutzerdefinierte Metadaten für dieses Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="907ca-150">Generates a web request to return the properties and user-defined metadata for this directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-151">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="907ca-151">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List (uri, timeout, listingContext, useVersionHeader, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="907ca-152">Der absolute URI zur Freigabe.</span><span class="sxs-lookup"><span data-stu-id="907ca-152">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-153">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-153">The server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="907ca-154">Ein Satz von Parametern für die Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="907ca-154">A set of parameters for the listing operation.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-155">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="907ca-155">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-156">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-156">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-157">Generiert eine webanforderung um eine Liste aller Dateien und Unterverzeichnisse im Verzeichnis zurück.</span><span class="sxs-lookup"><span data-stu-id="907ca-157">Generates a web request to return a listing of all files and subdirectories in the directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-158">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="907ca-158">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, Nullable&lt;DateTimeOffset&gt; shareSnapshot, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext,System.Nullable{System.DateTimeOffset},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext * Nullable&lt;DateTimeOffset&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List (uri, timeout, listingContext, shareSnapshot, useVersionHeader, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="907ca-159">Der absolute URI zur Freigabe.</span><span class="sxs-lookup"><span data-stu-id="907ca-159">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-160">Das Servertimeout-Intervall.</span><span class="sxs-lookup"><span data-stu-id="907ca-160">The server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="907ca-161">Ein Satz von Parametern für die Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="907ca-161">A set of parameters for the listing operation.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="907ca-162">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel Freigabe angeben, wenn die Freigabe eine Momentaufnahme ist.</span><span class="sxs-lookup"><span data-stu-id="907ca-162">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-163">Ein Flag, der angibt, ob der HTTP-Header X-ms-Version festgelegt.</span><span class="sxs-lookup"><span data-stu-id="907ca-163">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-164">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-165">Generiert eine webanforderung um eine Liste aller Dateien und Unterverzeichnisse im Verzeichnis zurück.</span><span class="sxs-lookup"><span data-stu-id="907ca-165">Generates a web request to return a listing of all files and subdirectories in the directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-166">Eine webanforderung zu verwenden, um den Vorgang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="907ca-166">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="907ca-167">Ein <see cref="T:System.Uri" /> , den absoluten URI zum Ziel-Blob angibt.</span><span class="sxs-lookup"><span data-stu-id="907ca-167">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="907ca-168">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="907ca-168">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="907ca-169">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</span><span class="sxs-lookup"><span data-stu-id="907ca-169">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="907ca-170">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="907ca-170">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="907ca-171">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="907ca-171">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="907ca-172">Erstellt eine webanforderung benutzerdefinierte Metadaten für das Verzeichnis festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="907ca-172">Constructs a web request to set user-defined metadata for the directory.</span></span>
            </summary>
        <returns><span data-ttu-id="907ca-173">eine webanforderung für den Vorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="907ca-173">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>