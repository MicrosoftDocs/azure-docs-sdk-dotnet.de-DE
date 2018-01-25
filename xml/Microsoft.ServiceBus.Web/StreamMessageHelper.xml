<Type Name="StreamMessageHelper" FullName="Microsoft.ServiceBus.Web.StreamMessageHelper">
  <TypeSignature Language="C#" Value="public static class StreamMessageHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StreamMessageHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Web.StreamMessageHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class StreamMessageHelper" />
  <TypeSignature Language="F#" Value="type StreamMessageHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d7b39-101">Hilfsklasse zum Erstellen eines Message-Objekts von streaming-Inhalte.</span><span class="sxs-lookup"><span data-stu-id="d7b39-101">Helper class for creating a Message object from streaming content.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateJsonMessage">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Message CreateJsonMessage (System.ServiceModel.Channels.MessageVersion version, string action, System.IO.Stream jsonStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Message CreateJsonMessage(class System.ServiceModel.Channels.MessageVersion version, string action, class System.IO.Stream jsonStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateJsonMessage(System.ServiceModel.Channels.MessageVersion,System.String,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateJsonMessage (version As MessageVersion, action As String, jsonStream As Stream) As Message" />
      <MemberSignature Language="F#" Value="static member CreateJsonMessage : System.ServiceModel.Channels.MessageVersion * string * System.IO.Stream -&gt; System.ServiceModel.Channels.Message" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.CreateJsonMessage (version, action, jsonStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Message</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.ServiceModel.Channels.MessageVersion" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="jsonStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="version"> <span data-ttu-id="d7b39-102">Die Nachrichtenversion.</span><span class="sxs-lookup"><span data-stu-id="d7b39-102">The message version.</span></span></param>
        <param name="action"> <span data-ttu-id="d7b39-103">Beschreibt, wie die Nachricht verarbeitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7b39-103">A description of how the message should be processed.</span></span></param>
        <param name="jsonStream"> <span data-ttu-id="d7b39-104">Ein Datenstrom, der zum Schreiben von Text in der neuen Nachricht Inhalt enthält.</span><span class="sxs-lookup"><span data-stu-id="d7b39-104">A stream that contains content used to write the body of the new message.</span></span></param>
        <summary><span data-ttu-id="d7b39-105">Erstellt eine JSON-Nachricht mit einer angegebenen Version.</span><span class="sxs-lookup"><span data-stu-id="d7b39-105">Creates a JSON message with a specified version.</span></span></summary>
        <returns><span data-ttu-id="d7b39-106">Die erstellte JSON-Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d7b39-106">The created JSON message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessage">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Message CreateMessage (System.ServiceModel.Channels.MessageVersion version, string action, Microsoft.ServiceBus.Web.StreamWriterDelegate writer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Message CreateMessage(class System.ServiceModel.Channels.MessageVersion version, string action, class Microsoft.ServiceBus.Web.StreamWriterDelegate writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage(System.ServiceModel.Channels.MessageVersion,System.String,Microsoft.ServiceBus.Web.StreamWriterDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateMessage (version As MessageVersion, action As String, writer As StreamWriterDelegate) As Message" />
      <MemberSignature Language="F#" Value="static member CreateMessage : System.ServiceModel.Channels.MessageVersion * string * Microsoft.ServiceBus.Web.StreamWriterDelegate -&gt; System.ServiceModel.Channels.Message" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage (version, action, writer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Message</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.ServiceModel.Channels.MessageVersion" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="writer" Type="Microsoft.ServiceBus.Web.StreamWriterDelegate" />
      </Parameters>
      <Docs>
        <param name="version"> <span data-ttu-id="d7b39-107">Gibt an, die Adressierung und Umschlag-Versionen, die für die neu erstellte Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="d7b39-107">Specifies the addressing and envelope versions to use for the newly created message.</span></span> <span data-ttu-id="d7b39-108">Wenn die Anforderung erfolgt mithilfe von REST, die Addressing und Umschlag Version wird keine.</span><span class="sxs-lookup"><span data-stu-id="d7b39-108">If the request is made using REST, the Addressing and Envelope version are None.</span></span></param>
        <param name="action"> <span data-ttu-id="d7b39-109">Beschreibt, wie die Nachricht verarbeitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7b39-109">A description of how the message should be processed.</span></span> <span data-ttu-id="d7b39-110">Für Nachrichten, die als Antwort auf eine HTTP-Anforderung gesendet werden muss dieser Wert "GETRESPONSE" sein.</span><span class="sxs-lookup"><span data-stu-id="d7b39-110">For messages sent in response to a HTTP request, this value must be “GETRESPONSE”.</span></span></param>
        <param name="writer"> <span data-ttu-id="d7b39-111">Ein Delegat, der ermöglicht<see cref="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage" /> Rückruf und bitten Sie für einen Datenstrom zum Auffüllen der Text der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d7b39-111">A delegate that allows<see cref="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage" /> to call back and ask for a Stream to populate the body of the message.</span></span></param>
        <summary><span data-ttu-id="d7b39-112">Erstellt eine Nachricht aus einem Stream und mit der angegebenen Version, Aktion und Delegaten.</span><span class="sxs-lookup"><span data-stu-id="d7b39-112">Creates a message from a stream, using the specified version, action, and delegate.</span></span></summary>
        <returns><span data-ttu-id="d7b39-113">Gibt einen Stream erstellt<see cref="T:System.ServiceModel.Channels.Message" />.</span><span class="sxs-lookup"><span data-stu-id="d7b39-113">Returns a stream-created<see cref="T:System.ServiceModel.Channels.Message" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessage">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Message CreateMessage (System.ServiceModel.Channels.MessageVersion version, string action, System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Message CreateMessage(class System.ServiceModel.Channels.MessageVersion version, string action, class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage(System.ServiceModel.Channels.MessageVersion,System.String,System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member CreateMessage : System.ServiceModel.Channels.MessageVersion * string * System.IO.Stream -&gt; System.ServiceModel.Channels.Message" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage (version, action, stream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Message</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.ServiceModel.Channels.MessageVersion" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="version"> <span data-ttu-id="d7b39-114">Gibt an, die Adressierung und Umschlag-Versionen, die für die neu erstellte Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="d7b39-114">Specifies the addressing and envelope versions to use for the newly created message.</span></span> <span data-ttu-id="d7b39-115">Wenn die Anforderung erfolgt mithilfe von REST, die Addressing und Umschlag Version wird keine.</span><span class="sxs-lookup"><span data-stu-id="d7b39-115">If the request is made using REST, the Addressing and Envelope version are None.</span></span></param>
        <param name="action"> <span data-ttu-id="d7b39-116">Beschreibt, wie die Nachricht verarbeitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7b39-116">A description of how the message should be processed.</span></span> <span data-ttu-id="d7b39-117">Für Nachrichten, die als Antwort auf eine HTTP-Anforderung gesendet werden muss dieser Wert "GETRESPONSE" sein.</span><span class="sxs-lookup"><span data-stu-id="d7b39-117">For messages sent in response to a HTTP request, this value must be “GETRESPONSE”.</span></span></param>
        <param name="stream"> <span data-ttu-id="d7b39-118">Ein Datenstrom, der zum Schreiben von Text in der neuen Nachricht Inhalt enthält.</span><span class="sxs-lookup"><span data-stu-id="d7b39-118">A stream that contains content used to write the body of the new message.</span></span></param>
        <summary><span data-ttu-id="d7b39-119">Erstellt eine Nachricht mit der angegebenen Version, Aktion und Datenstrom.</span><span class="sxs-lookup"><span data-stu-id="d7b39-119">Creates a message, using the specified version, action, and stream.</span></span></summary>
        <returns><span data-ttu-id="d7b39-120">Gibt einen Stream erstellt<see cref="T:System.ServiceModel.Channels.Message" />.</span><span class="sxs-lookup"><span data-stu-id="d7b39-120">Returns a stream-created<see cref="T:System.ServiceModel.Channels.Message" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStream">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetStream (System.ServiceModel.Channels.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetStream(class System.ServiceModel.Channels.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream(System.ServiceModel.Channels.Message)" />
      <MemberSignature Language="F#" Value="static member GetStream : System.ServiceModel.Channels.Message -&gt; System.IO.Stream" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.ServiceModel.Channels.Message" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="d7b39-121">Die Meldung.</span><span class="sxs-lookup"><span data-stu-id="d7b39-121">The message.</span></span></param>
        <summary><span data-ttu-id="d7b39-122">Ruft den Datenstrom der angegebenen Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="d7b39-122">Retrieves the stream of the specified message.</span></span></summary>
        <returns><span data-ttu-id="d7b39-123">Gibt eine<see cref="T:System.IO.Stream" /> , die den Stream der Nachricht enthält.</span><span class="sxs-lookup"><span data-stu-id="d7b39-123">Returns a<see cref="T:System.IO.Stream" /> that contains the stream of the message.</span></span> <span data-ttu-id="d7b39-124">Ein Datenstrom wird immer zurückgegeben, unabhängig davon, ob der Nachrichtentext leer ist.</span><span class="sxs-lookup"><span data-stu-id="d7b39-124">A Stream is always returned regardless of whether the message body is empty.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStream">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetStream (System.Xml.XmlDictionaryReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetStream(class System.Xml.XmlDictionaryReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream(System.Xml.XmlDictionaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetStream (reader As XmlDictionaryReader) As Stream" />
      <MemberSignature Language="F#" Value="static member GetStream : System.Xml.XmlDictionaryReader -&gt; System.IO.Stream" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlDictionaryReader" />
      </Parameters>
      <Docs>
        <param name="reader"> <span data-ttu-id="d7b39-125">Der Reader.</span><span class="sxs-lookup"><span data-stu-id="d7b39-125">The reader.</span></span></param>
        <summary><span data-ttu-id="d7b39-126">Ruft den Datenstrom der angegebenen Nachricht mit dem angegebenen Reader ab.</span><span class="sxs-lookup"><span data-stu-id="d7b39-126">Retrieves the stream of the specified message with the specified reader.</span></span></summary>
        <returns><span data-ttu-id="d7b39-127">Der Datenstrom der angegebenen Meldung.</span><span class="sxs-lookup"><span data-stu-id="d7b39-127">The stream of the specified message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>