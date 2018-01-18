<Type Name="DeviceMaximumQueueDepthExceededException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException">
  <TypeSignature Language="C#" Value="public sealed class DeviceMaximumQueueDepthExceededException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit DeviceMaximumQueueDepthExceededException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceMaximumQueueDepthExceededException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceMaximumQueueDepthExceededException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="144c3-101">Die Ausnahme, die ausgelöst wird, wenn der Versuch, in die Warteschlange einreihen einer Nachricht fehlschlägt, weil die Nachrichtenwarteschlange für das Gerät bereits voll ist.</span><span class="sxs-lookup"><span data-stu-id="144c3-101">The exception that is thrown when an attempt to enqueue a message fails because the message queue for the device is already full.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMaximumQueueDepthExceededException (int maximumQueueDepth);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maximumQueueDepth) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maximumQueueDepth As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException : int -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException maximumQueueDepth" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maximumQueueDepth" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maximumQueueDepth"><span data-ttu-id="144c3-102">Maximale Anzahl der Nachrichten in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="144c3-102">Maximum number of messages in the queue.</span></span></param>
        <summary>
            <span data-ttu-id="144c3-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> Klasse mit der Meldungszeichenfolge, die den Bezeichner des bereits vorhandenen Geräts enthält.</span><span class="sxs-lookup"><span data-stu-id="144c3-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> class with the message string containing the identifier of the already existing device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMaximumQueueDepthExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="144c3-104">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="144c3-104">A description of the error.</span></span> <span data-ttu-id="144c3-105">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="144c3-105">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="144c3-106">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="144c3-106">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="144c3-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter.</span><span class="sxs-lookup"><span data-stu-id="144c3-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> class with the message string set to the message parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMaximumQueueDepthExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="144c3-108">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="144c3-108">A description of the error.</span></span> <span data-ttu-id="144c3-109">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="144c3-109">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="144c3-110">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="144c3-110">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="144c3-111">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="144c3-111">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="144c3-112">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="144c3-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> class with the message string set to the message parameter and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>