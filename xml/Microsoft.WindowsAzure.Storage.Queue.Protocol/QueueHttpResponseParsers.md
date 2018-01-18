<Type Name="QueueHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class QueueHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type QueueHttpResponseParsers = class" />
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
            <span data-ttu-id="a8132-101">Stellt einen Satz von Methoden für die Analyse einer Antwort mit Warteschlangendaten aus dem Warteschlangendienst bereit.</span><span class="sxs-lookup"><span data-stu-id="a8132-101">Provides a set of methods for parsing a response containing queue data from the Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApproximateMessageCount">
      <MemberSignature Language="C#" Value="public static string GetApproximateMessageCount (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetApproximateMessageCount(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetApproximateMessageCount(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetApproximateMessageCount (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetApproximateMessageCount : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetApproximateMessageCount response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="a8132-102">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="a8132-102">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-103">Ruft die ungefähre Nachrichtenanzahl für die Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="a8132-103">Gets the approximate message count for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-104">Die ungefähre Anzahl für die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="a8132-104">The approximate count for the queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetMetadata response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="a8132-105">Die Antwort vom Server.</span><span class="sxs-lookup"><span data-stu-id="a8132-105">The response from server.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-106">Ruft die benutzerdefinierten Metadaten ab.</span><span class="sxs-lookup"><span data-stu-id="a8132-106">Gets the user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-107">Ein Objekt des Typs <see cref="T:System.Collections.IDictionary" /> mit den Metadaten.</span><span class="sxs-lookup"><span data-stu-id="a8132-107">An object of type <see cref="T:System.Collections.IDictionary" /> containing the metadata.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextVisibleTime">
      <MemberSignature Language="C#" Value="public static DateTime GetNextVisibleTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype System.DateTime GetNextVisibleTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetNextVisibleTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNextVisibleTime (response As HttpWebResponse) As DateTime" />
      <MemberSignature Language="F#" Value="static member GetNextVisibleTime : System.Net.HttpWebResponse -&gt; DateTime" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetNextVisibleTime response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="a8132-108">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="a8132-108">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-109">Extrahiert das nächste Mal für die Sichtbarkeit von einer Web-Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="a8132-109">Extracts the next visibility time from a web response header.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-110">Der Zeitpunkt des nächsten Sichtbarkeit, die im Header der Antwort gespeichert.</span><span class="sxs-lookup"><span data-stu-id="a8132-110">The time of next visibility stored in the header of the response.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPopReceipt">
      <MemberSignature Language="C#" Value="public static string GetPopReceipt (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetPopReceipt(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetPopReceipt(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetPopReceipt (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetPopReceipt : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetPopReceipt response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="a8132-111">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="a8132-111">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-112">Extrahiert die abrufbestätigung einen Web-Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="a8132-112">Extracts the pop receipt from a web response header.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-113">Die abrufbestätigung, die im Header der Antwort gespeichert.</span><span class="sxs-lookup"><span data-stu-id="a8132-113">The pop receipt stored in the header of the response.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetRequestId response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="a8132-114">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="a8132-114">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-115">Ruft die Anforderungs-ID aus der Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="a8132-115">Gets the request ID from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-116">Ein eindeutiger Wert, der der Anforderung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="a8132-116">A unique value associated with the request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceProperties inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="a8132-117">Der Stream, aus dem die Diensteigenschaften gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a8132-117">The stream from which to read the service properties.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-118">Liest die Diensteigenschaften aus einem Stream.</span><span class="sxs-lookup"><span data-stu-id="a8132-118">Reads service properties from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-119">Die Diensteigenschaften, die im Stream gespeichert.</span><span class="sxs-lookup"><span data-stu-id="a8132-119">The service properties stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="a8132-120">Der Stream, aus dem die dienststatistik gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a8132-120">The stream from which to read the service stats.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-121">Liest dienststatistik aus einem Stream.</span><span class="sxs-lookup"><span data-stu-id="a8132-121">Reads service stats from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="a8132-122">Die dienststatistik im Stream gespeichert.</span><span class="sxs-lookup"><span data-stu-id="a8132-122">The service stats stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As QueuePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="a8132-123">Der Datenstrom des XML-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="a8132-123">The stream of XML policies.</span></span></param>
        <param name="permissions"><span data-ttu-id="a8132-124">Das Berechtigungen-Objekt, das auf dem die Richtlinien, die zu schreibenden sind.</span><span class="sxs-lookup"><span data-stu-id="a8132-124">The permissions object to which the policies are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="a8132-125">Liest die Zugriffsrichtlinien für die Freigabe aus einem Datenstrom im XML-Format an.</span><span class="sxs-lookup"><span data-stu-id="a8132-125">Reads the share access policies from a stream in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>