<Type Name="GetMessagesResponse" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse">
  <TypeSignature Language="C#" Value="public sealed class GetMessagesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GetMessagesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GetMessagesResponse&#xA;Inherits ResponseParsingBase(Of QueueMessage)" />
  <TypeSignature Language="F#" Value="type GetMessagesResponse = class&#xA;    inherit ResponseParsingBase&lt;QueueMessage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6589a-101">Stellt Methoden zum Analysieren der Antwort aus einem Vorgang zum Abrufen von Nachrichten aus einer Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="6589a-101">Provides methods for parsing the response from an operation to get messages from a queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetMessagesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse" Usage="new Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="6589a-102">Der Datenstrom von Nachrichten analysiert.</span><span class="sxs-lookup"><span data-stu-id="6589a-102">The stream of messages to parse.</span></span></param>
        <summary>
            <span data-ttu-id="6589a-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6589a-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Messages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt; Messages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt; Messages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse.Messages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Messages As IEnumerable(Of QueueMessage)" />
      <MemberSignature Language="F#" Value="member this.Messages : seq&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse.Messages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6589a-104">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" /> Objekte aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="6589a-104">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" /> objects from the response.</span></span>
            </summary>
        <value><span data-ttu-id="6589a-105">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="6589a-105">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.GetMessagesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of QueueMessage)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;" Usage="getMessagesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6589a-106">Analysiert die XML-Antwort von einem Vorgang zum Abrufen von Nachrichten aus einer Warteschlange zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6589a-106">Parses the XML response returned by an operation to get messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="6589a-107">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="6589a-107">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>