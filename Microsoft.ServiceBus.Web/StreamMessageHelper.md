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
    <summary>Hilfsklasse zum Erstellen eines Message-Objekts von streaming-Inhalte.</summary>
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
        <param name="version"> Die Nachrichtenversion.</param>
        <param name="action"> Beschreibt, wie die Nachricht verarbeitet werden soll.</param>
        <param name="jsonStream"> Ein Datenstrom, der zum Schreiben von Text in der neuen Nachricht Inhalt enthält.</param>
        <summary>Erstellt eine JSON-Nachricht mit einer angegebenen Version.</summary>
        <returns>Die erstellte JSON-Nachricht.</returns>
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
        <param name="version"> Gibt an, die Adressierung und Umschlag-Versionen, die für die neu erstellte Nachricht verwendet. Wenn die Anforderung erfolgt mithilfe von REST, die Addressing und Umschlag Version wird keine.</param>
        <param name="action"> Beschreibt, wie die Nachricht verarbeitet werden soll. Für Nachrichten, die als Antwort auf eine HTTP-Anforderung gesendet werden muss dieser Wert "GETRESPONSE" sein.</param>
        <param name="writer"> Ein Delegat, der ermöglicht<see cref="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage" /> Rückruf und bitten Sie für einen Datenstrom zum Auffüllen der Text der Nachricht.</param>
        <summary>Erstellt eine Nachricht aus einem Stream und mit der angegebenen Version, Aktion und Delegaten.</summary>
        <returns>Gibt einen Stream erstellt<see cref="T:System.ServiceModel.Channels.Message" />.</returns>
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
        <param name="version"> Gibt an, die Adressierung und Umschlag-Versionen, die für die neu erstellte Nachricht verwendet. Wenn die Anforderung erfolgt mithilfe von REST, die Addressing und Umschlag Version wird keine.</param>
        <param name="action"> Beschreibt, wie die Nachricht verarbeitet werden soll. Für Nachrichten, die als Antwort auf eine HTTP-Anforderung gesendet werden muss dieser Wert "GETRESPONSE" sein.</param>
        <param name="stream"> Ein Datenstrom, der zum Schreiben von Text in der neuen Nachricht Inhalt enthält.</param>
        <summary>Erstellt eine Nachricht mit der angegebenen Version, Aktion und Datenstrom.</summary>
        <returns>Gibt einen Stream erstellt<see cref="T:System.ServiceModel.Channels.Message" />.</returns>
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
        <param name="message"> Die Meldung.</param>
        <summary>Ruft den Datenstrom der angegebenen Nachricht ab.</summary>
        <returns>Gibt eine<see cref="T:System.IO.Stream" /> , die den Stream der Nachricht enthält. Ein Datenstrom wird immer zurückgegeben, unabhängig davon, ob der Nachrichtentext leer ist.</returns>
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
        <param name="reader"> Der Reader.</param>
        <summary>Ruft den Datenstrom der angegebenen Nachricht mit dem angegebenen Reader ab.</summary>
        <returns>Der Datenstrom der angegebenen Meldung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>