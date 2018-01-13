<Type Name="ShareHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class ShareHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShareHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class ShareHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type ShareHttpResponseParsers = class" />
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
            <span data-ttu-id="3db08-101">Stellt Methoden zum Analysieren Antworten auf Vorgänge für Freigaben im Dateidienst bereit.</span><span class="sxs-lookup"><span data-stu-id="3db08-101">Provides methods for parsing responses to operations on shares in the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetMetadata response" />
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
        <param name="response"><span data-ttu-id="3db08-102">Die Antwort vom Server.</span><span class="sxs-lookup"><span data-stu-id="3db08-102">The response from server.</span></span></param>
        <summary>
            <span data-ttu-id="3db08-103">Ruft die benutzerdefinierten Metadaten ab.</span><span class="sxs-lookup"><span data-stu-id="3db08-103">Gets the user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="3db08-104">Ein <see cref="T:System.Collections.IDictionary" /> der Metadaten.</span><span class="sxs-lookup"><span data-stu-id="3db08-104">A <see cref="T:System.Collections.IDictionary" /> of the metadata.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.FileShareProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.FileShareProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As FileShareProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.File.FileShareProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileShareProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="3db08-105">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="3db08-105">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="3db08-106">Ruft die Eigenschaften der Freigabe aus der Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="3db08-106">Gets the share's properties from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="3db08-107">Attribute für die Freigabe.</span><span class="sxs-lookup"><span data-stu-id="3db08-107">The share's attributes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetRequestId response" />
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
        <param name="response"><span data-ttu-id="3db08-108">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="3db08-108">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="3db08-109">Ruft die Anforderungs-ID aus der Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="3db08-109">Gets the request ID from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="3db08-110">Ein eindeutiger Wert, der der Anforderung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="3db08-110">A unique value associated with the request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSnapshotTime">
      <MemberSignature Language="C#" Value="public static string GetSnapshotTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSnapshotTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetSnapshotTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSnapshotTime (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetSnapshotTime : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetSnapshotTime response" />
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
        <param name="response"><span data-ttu-id="3db08-111">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="3db08-111">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="3db08-112">Ruft den Momentaufnahme-Zeitstempel aus der Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="3db08-112">Gets the snapshot timestamp from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="3db08-113">Der Momentaufnahme-Zeitstempel.</span><span class="sxs-lookup"><span data-stu-id="3db08-113">The snapshot timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.FileSharePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As FileSharePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.FileSharePermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="3db08-114">Der Datenstrom des XML-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="3db08-114">The stream of XML policies.</span></span></param>
        <param name="permissions"><span data-ttu-id="3db08-115">Das Berechtigungen-Objekt, das auf dem die Richtlinien, die zu schreibenden sind.</span><span class="sxs-lookup"><span data-stu-id="3db08-115">The permissions object to which the policies are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="3db08-116">Liest die Zugriffsrichtlinien für die Freigabe aus einem Datenstrom im XML-Format an.</span><span class="sxs-lookup"><span data-stu-id="3db08-116">Reads the share access policies from a stream in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadShareStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats ReadShareStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats ReadShareStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadShareStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadShareStats (inputStream As Stream) As ShareStats" />
      <MemberSignature Language="F#" Value="static member ReadShareStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadShareStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="3db08-117">Der Stream, aus dem die freigabestatistiken gelesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="3db08-117">The stream from which to read the share stats.</span></span></param>
        <summary>
            <span data-ttu-id="3db08-118">Lesevorgänge freigeben Stats aus einem Stream.</span><span class="sxs-lookup"><span data-stu-id="3db08-118">Reads share stats from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="3db08-119">Die freigabestatistiken im Stream gespeichert.</span><span class="sxs-lookup"><span data-stu-id="3db08-119">The share stats stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>