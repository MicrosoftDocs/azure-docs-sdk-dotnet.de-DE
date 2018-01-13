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
            Stellt zusätzliche Funktionen für die Verarbeitung von erweiterten Fehlerinformationen, die von Windows Azure-Speicherdienste für Tabellen zurückgegeben.
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
        <param name="inputStream">Der Datenstrom, zu analysieren.</param>
        <summary>
            Analysiert die Fehlerdetails aus dem stream
            </summary>
        <returns>Die Fehlerdetails.</returns>
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
        <param name="responseStream">Der Datenstrom, zu analysieren.</param>
        <param name="cancellationToken">Das Abbruchtoken verwendet, um die Anforderung abzubrechen.</param>
        <summary>
            Analysiert die Fehlerdetails aus dem Stream.
            </summary>
        <returns>Die Fehlerdetails.</returns>
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
        <param name="inputStream">Der Eingabestream.</param>
        <param name="response">Die Webantwort.</param>
        <param name="contentType">Der Inhaltstyp der Antwort.</param>
        <summary>
            Ruft die Fehlerdetails aus dem Stream ab.
            </summary>
        <returns>Die Fehlerdetails.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>