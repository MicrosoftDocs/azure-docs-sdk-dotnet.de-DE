<Type Name="ODataErrorHelper" FullName="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper">
  <TypeSignature Language="C#" Value="public static class ODataErrorHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ODataErrorHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class ODataErrorHelper" />
  <TypeSignature Language="F#" Value="type ODataErrorHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2664c-101">Stellt zusätzliche Funktionen für die Verarbeitung von erweiterten Fehlerinformationen, die von Windows Azure-Speicherdienste für Tabellen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2664c-101">Represents additional functionality for processing extended error information returned by the Windows Azure storage services for Tables.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ReadAndParseExtendedError">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadAndParseExtendedError (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadAndParseExtendedError(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedError(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadAndParseExtendedError (inputStream As Stream) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadAndParseExtendedError : System.IO.Stream -&gt; Microsoft.Azure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedError inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="2664c-102">Der Datenstrom, zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="2664c-102">The stream to parse.</span></span></param>
        <summary>
            <span data-ttu-id="2664c-103">Analysiert die Fehlerdetails aus dem stream</span><span class="sxs-lookup"><span data-stu-id="2664c-103">Parses the error details from the stream</span></span>
            </summary>
        <returns><span data-ttu-id="2664c-104">Die Fehlerdetails.</span><span class="sxs-lookup"><span data-stu-id="2664c-104">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAndParseExtendedErrorAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt; ReadAndParseExtendedErrorAsync (System.IO.Stream responseStream, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt; ReadAndParseExtendedErrorAsync(class System.IO.Stream responseStream, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedErrorAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReadAndParseExtendedErrorAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt;" Usage="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedErrorAsync (responseStream, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.CosmosDB.Table.ODataErrorHelper/&lt;ReadAndParseExtendedErrorAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="responseStream" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="responseStream"><span data-ttu-id="2664c-105">Der Datenstrom, zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="2664c-105">The stream to parse.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="2664c-106">Das Abbruchtoken verwendet, um die Anforderung abzubrechen.</span><span class="sxs-lookup"><span data-stu-id="2664c-106">Cancellation token used to cancel the request.</span></span></param>
        <summary>
            <span data-ttu-id="2664c-107">Analysiert die Fehlerdetails aus dem Stream.</span><span class="sxs-lookup"><span data-stu-id="2664c-107">Parses the error details from the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="2664c-108">Die Fehlerdetails.</span><span class="sxs-lookup"><span data-stu-id="2664c-108">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadFromStreamUsingODataLib">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadFromStreamUsingODataLib (System.IO.Stream inputStream, System.Net.HttpWebResponse response, string contentType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadFromStreamUsingODataLib(class System.IO.Stream inputStream, class System.Net.HttpWebResponse response, string contentType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadFromStreamUsingODataLib(System.IO.Stream,System.Net.HttpWebResponse,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadFromStreamUsingODataLib (inputStream As Stream, response As HttpWebResponse, contentType As String) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadFromStreamUsingODataLib : System.IO.Stream * System.Net.HttpWebResponse * string -&gt; Microsoft.Azure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadFromStreamUsingODataLib (inputStream, response, contentType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
        <Parameter Name="contentType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="2664c-109">Der Eingabestream.</span><span class="sxs-lookup"><span data-stu-id="2664c-109">The input stream.</span></span></param>
        <param name="response"><span data-ttu-id="2664c-110">Die Webantwort.</span><span class="sxs-lookup"><span data-stu-id="2664c-110">The web response.</span></span></param>
        <param name="contentType"><span data-ttu-id="2664c-111">Der Inhaltstyp der Antwort.</span><span class="sxs-lookup"><span data-stu-id="2664c-111">The response Content-Type.</span></span></param>
        <summary>
            <span data-ttu-id="2664c-112">Ruft die Fehlerdetails aus dem Stream ab.</span><span class="sxs-lookup"><span data-stu-id="2664c-112">Gets the error details from the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="2664c-113">Die Fehlerdetails.</span><span class="sxs-lookup"><span data-stu-id="2664c-113">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>