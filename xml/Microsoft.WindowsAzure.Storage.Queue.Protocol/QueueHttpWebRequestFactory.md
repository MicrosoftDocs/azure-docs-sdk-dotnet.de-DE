<Type Name="QueueHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class QueueHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type QueueHttpWebRequestFactory = class" />
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
            <span data-ttu-id="fd8ed-101">Eine Factoryklasse zum Erstellen einer webanforderung zum Verwalten von Warteschlangen im Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-101">A factory class for constructing a web request to manage queues in the Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, operationContext)" />
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
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-102">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-103">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-103">An integer specifying the server timeout interval.</span></span></param>
        <param name="timeToLiveInSeconds"><span data-ttu-id="fd8ed-104">Die Meldung, die Time-to-live, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-104">The message time-to-live, in seconds.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="fd8ed-105">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-105">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-106">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-106">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-107">Erstellt eine webanforderung zum Hinzufügen einer Nachricht für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-107">Constructs a web request to add a message for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-108">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-108">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-109">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-109">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-110">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-110">An integer specifying the server timeout interval.</span></span></param>
        <param name="timeToLiveInSeconds"><span data-ttu-id="fd8ed-111">Die Meldung, die Time-to-live, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-111">The message time-to-live, in seconds.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="fd8ed-112">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-112">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-113">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-113">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-114">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-114">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-115">Erstellt eine webanforderung zum Hinzufügen einer Nachricht für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-115">Constructs a web request to add a message for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-116">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-116">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><span data-ttu-id="fd8ed-117">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-117">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="metadata"><span data-ttu-id="fd8ed-118">Ein <see cref="T:System.Collections.Generic.Dictionary`2" /> Objekt, das die benutzerdefinierten Metadaten enthält.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-118">A <see cref="T:System.Collections.Generic.Dictionary`2" /> object containing the user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-119">Fügt benutzerdefinierte Metadaten für die Anforderung als ein oder mehrere Name-Wert-Paare hinzu.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-119">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><span data-ttu-id="fd8ed-120">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-120">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="name"><span data-ttu-id="fd8ed-121">Eine Zeichenfolge, enthält der Name der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-121">A string containing the metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="fd8ed-122">Eine Zeichenfolge, die den Metadatenwert enthält.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-122">A string containing the metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-123">Fügt benutzerdefinierte Metadaten für die Anforderung als ein einzelnes Name-Wert-Paar hinzu.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-123">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-124">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-124">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-125">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-125">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-126">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-126">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-127">Erstellt eine webanforderung zum Löschen alle Nachrichten in der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-127">Constructs a web request to clear all messages in the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-128">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-128">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-129">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-129">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-130">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-130">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-131">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-131">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-132">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-132">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-133">Erstellt eine webanforderung zum Löschen alle Nachrichten in der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-133">Constructs a web request to clear all messages in the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-134">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-134">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-135">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-135">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-136">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-136">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-137">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-137">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-138">Erstellt eine webanforderung zum Erstellen einer neuen Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-138">Constructs a web request to create a new queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-139">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-139">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-140">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-140">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-141">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-141">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-142">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-142">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-143">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-144">Erstellt eine webanforderung zum Erstellen einer neuen Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-144">Constructs a web request to create a new queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-145">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-145">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-146">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-146">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-147">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-147">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-148">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-148">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-149">Erstellt eine webanforderung an die Warteschlange und alle darin enthaltenen Nachrichten löschen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-149">Constructs a web request to delete the queue and all of the messages within it.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-150">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-150">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-151">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-151">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-152">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-152">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-153">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-153">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-154">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-154">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-155">Erstellt eine webanforderung an die Warteschlange und alle darin enthaltenen Nachrichten löschen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-155">Constructs a web request to delete the queue and all of the messages within it.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-156">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-156">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-157">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-157">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-158">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-158">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="fd8ed-159">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-159">A string specifying the pop receipt of the message.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-160">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-160">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-161">Erstellt eine webanforderung um eine Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-161">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-162">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-162">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, useVersionHeader, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-163">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-163">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-164">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-164">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="fd8ed-165">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-165">A string specifying the pop receipt of the message.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-166">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-166">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-167">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-167">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-168">Erstellt eine webanforderung um eine Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-168">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-169">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-169">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-170">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-170">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-171">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-171">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-172">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-172">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-173">Erstellt eine webanforderung, die ACL für eine Warteschlange zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-173">Constructs a web request to return the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-174">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-174">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-175">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-175">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-176">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-176">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-177">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-177">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-178">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-178">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-179">Erstellt eine webanforderung, die ACL für eine Warteschlange zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-179">Constructs a web request to return the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-180">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-180">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-181">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-181">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-182">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-182">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="fd8ed-183">Eine ganze Zahl, die die Anzahl der abzurufenden Nachrichten angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-183">An integer specifying the number of messages to get.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="fd8ed-184">Ein <see cref="T:System.TimeSpan" /> Wert, der das sichtbarkeitstimeout angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-184">A <see cref="T:System.TimeSpan" /> value specifying the visibility timeout.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-185">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-185">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-186">Erstellt eine webanforderung zum Abrufen von Nachrichten aus einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-186">Constructs a web request to get messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-187">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-187">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-188">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-188">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-189">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-189">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="fd8ed-190">Eine ganze Zahl, die die Anzahl der abzurufenden Nachrichten angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-190">An integer specifying the number of messages to get.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="fd8ed-191">Ein <see cref="T:System.TimeSpan" /> Wert, der das sichtbarkeitstimeout angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-191">A <see cref="T:System.TimeSpan" /> value specifying the visibility timeout.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-192">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-192">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-193">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-193">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-194">Erstellt eine webanforderung zum Abrufen von Nachrichten aus einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-194">Constructs a web request to get messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-195">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-195">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-196">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-196">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-197">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-197">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-198">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-198">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-199">Generiert eine webanforderung, die benutzerdefinierten Metadaten für diese Warteschlange zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-199">Generates a web request to return the user-defined metadata for this queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-200">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-200">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-201">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-201">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-202">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-202">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-203">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-203">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-204">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-204">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-205">Generiert eine webanforderung, die benutzerdefinierten Metadaten für diese Warteschlange zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-205">Generates a web request to return the user-defined metadata for this queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-206">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-206">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-207">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-207">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="fd8ed-208">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-208">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-209">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-209">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-210">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-210">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-211">Erstellt eine webanforderung zum Abrufen der Eigenschaften des warteschlangendiensts.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-211">Creates a web request to get the properties of the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-212">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-212">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-213">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-213">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="fd8ed-214">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-215">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-215">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-216">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-216">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-217">Erstellt eine webanforderung zum Abrufen von Statistiken zum Warteschlangendienst.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-217">Creates a web request to get Queue service stats.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-218">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-218">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-219">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-219">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-220">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-220">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="fd8ed-221">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-221">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="fd8ed-222">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumerationswert ab, der angibt, ob warteschlangenmetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-222">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration value that indicates whether to return queue metadata with the listing.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-223">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-223">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-224">Erstellt eine webanforderung an eine Liste aller Warteschlangen, die in diesem Speicherkonto zurück.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-224">Constructs a web request to return a listing of all queues in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-225">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-225">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-226">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-226">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-227">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-227">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="fd8ed-228">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-228">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="fd8ed-229">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumerationswert ab, der angibt, ob warteschlangenmetadaten mit der Auflistung zurück.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-229">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration value that indicates whether to return queue metadata with the listing.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-230">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-230">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-231">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-231">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-232">Erstellt eine webanforderung an eine Liste aller Warteschlangen, die in diesem Speicherkonto zurück.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-232">Constructs a web request to return a listing of all queues in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-233">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-233">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-234">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-234">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-235">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-235">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="fd8ed-236">Eine ganze Zahl Festlegen der Anzahl von Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-236">An integer specifying the number of messages to peek.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-237">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-237">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-238">Erstellt eine webanforderung zum Einsehen von Nachrichten aus einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-238">Constructs a web request to peek messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-239">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-239">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, useVersionHeader, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-240">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-240">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-241">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-241">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="fd8ed-242">Eine ganze Zahl Festlegen der Anzahl von Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-242">An integer specifying the number of messages to peek.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-243">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-243">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-244">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-244">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-245">Erstellt eine webanforderung zum Einsehen von Nachrichten aus einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-245">Constructs a web request to peek messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-246">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-246">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-247">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-247">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-248">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-248">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-249">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-249">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-250">Erstellt eine webanforderung an die ACL für eine Warteschlange festgelegt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-250">Constructs a web request to set the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-251">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-251">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-252">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-252">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-253">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-253">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-254">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-254">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-255">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-255">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-256">Erstellt eine webanforderung an die ACL für eine Warteschlange festgelegt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-256">Constructs a web request to set the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-257">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-257">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-258">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-258">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-259">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-259">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-260">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-260">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-261">Generiert eine webanforderung benutzerdefinierte Metadaten für die Warteschlange festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-261">Generates a web request to set user-defined metadata for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-262">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-262">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="fd8ed-263">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-263">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-264">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-264">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-265">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-265">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-266">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-266">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-267">Generiert eine webanforderung benutzerdefinierte Metadaten für die Warteschlange festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-267">Generates a web request to set user-defined metadata for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-268">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-268">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-269">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-269">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="fd8ed-270">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-270">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-271">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-271">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-272">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-272">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-273">Erstellt eine webanforderung zum Festlegen der Eigenschaften des warteschlangendiensts an.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-273">Creates a web request to set the properties of the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-274">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-274">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-275">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-275">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-276">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-276">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="fd8ed-277">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-277">A string specifying the pop receipt of the message.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="fd8ed-278">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-278">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-279">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-279">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-280">Erstellt eine webanforderung um eine Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-280">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-281">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-281">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="fd8ed-282">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-282">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8ed-283">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-283">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="fd8ed-284">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-284">A string specifying the pop receipt of the message.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="fd8ed-285">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-285">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="fd8ed-286">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-286">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fd8ed-287">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-287">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-288">Erstellt eine webanforderung um eine Nachricht zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-288">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8ed-289">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-289">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="fd8ed-290">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-290">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="outputStream"><span data-ttu-id="fd8ed-291">Die <see cref="T:System.IO.Stream" /> auf das sind die formatierte Eigenschaften geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-291">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="fd8ed-292">Schreibt warteschlangendiensteigenschaften in einen Stream, in XML formatiert.</span><span class="sxs-lookup"><span data-stu-id="fd8ed-292">Writes Queue service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>