<Type Name="MessageTooLargeException" FullName="Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException">
  <TypeSignature Language="C#" Value="public sealed class MessageTooLargeException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessageTooLargeException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageTooLargeException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type MessageTooLargeException = class&#xA;    inherit IotHubException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Client.Exceptions.IotHubException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0c04-101">Die Ausnahme, die ausgelöst wird, wenn ein Versuch zum Senden einer Nachricht fehlschlägt, da die Länge der Nachricht die maximale zulässige Größe überschreitet.</span><span class="sxs-lookup"><span data-stu-id="c0c04-101">The exception that is thrown when an attempt to send a message fails because the length of the message exceeds the maximum size allowed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageTooLargeException (int maximumMessageSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maximumMessageSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maximumMessageSizeInBytes As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException : int -&gt; Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException maximumMessageSizeInBytes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maximumMessageSizeInBytes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maximumMessageSizeInBytes"><span data-ttu-id="c0c04-102">Gerätebezeichner, die bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c0c04-102">Device identifier that already exists.</span></span></param>
        <summary>
            <span data-ttu-id="c0c04-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> Klasse bei der die Meldungszeichenfolge, enthält die maximale Größe für eine Nachricht in Bytes zulässig.</span><span class="sxs-lookup"><span data-stu-id="c0c04-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> class with the message string containing the maximum sized allowed for a message, in bytes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageTooLargeException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c0c04-104">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="c0c04-104">A description of the error.</span></span> <span data-ttu-id="c0c04-105">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="c0c04-105">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="c0c04-106">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="c0c04-106">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="c0c04-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter.</span><span class="sxs-lookup"><span data-stu-id="c0c04-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> class with the message string set to the message parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageTooLargeException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c0c04-108">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="c0c04-108">A description of the error.</span></span> <span data-ttu-id="c0c04-109">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="c0c04-109">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="c0c04-110">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="c0c04-110">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="c0c04-111">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="c0c04-111">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="c0c04-112">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="c0c04-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> class with the message string set to the message parameter and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>