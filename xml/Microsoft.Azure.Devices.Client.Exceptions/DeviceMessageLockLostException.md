<Type Name="DeviceMessageLockLostException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException">
  <TypeSignature Language="C#" Value="public class DeviceMessageLockLostException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit DeviceMessageLockLostException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceMessageLockLostException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceMessageLockLostException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="85c8c-101">Die Ausnahme, die ausgelöst wird, wenn ein Versuch zur Kommunikation mit einem Gerät fehlschlägt, da das Sperrtoken unterbrochen wurde (wenn die Verbindung verloren geht und des z. B. wiedererlangen).</span><span class="sxs-lookup"><span data-stu-id="85c8c-101">The exception that is thrown when an attempt to communicate with a device fails because the lock token was lost (if the connection is lost and regained for example).</span></span> <span data-ttu-id="85c8c-102">Dieses Timeout hat dieselbe Wirkung, als ob die Nachricht Abandonned war.</span><span class="sxs-lookup"><span data-stu-id="85c8c-102">This timeout has the same effect as if the message was abandonned.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="85c8c-103">Fehlermeldung abgebrochen werden erneut in die Warteschlange eingereihten in der Warteschlange pro Gerät und der <see cref="T:Microsoft.Azure.Devices.Client.DeviceClient" /> Instanz erneut empfangen.</span><span class="sxs-lookup"><span data-stu-id="85c8c-103">An abandoned message will be re-enqueued in the per-device queue, and the <see cref="T:Microsoft.Azure.Devices.Client.DeviceClient" /> instance will receive it again.</span></span> <span data-ttu-id="85c8c-104">Eine abgelehnte Nachricht wird aus der Warteschlange gelöscht und nicht erneut vom Gerät empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="85c8c-104">A rejected message will be deleted from the queue and not received again by the device.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMessageLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="85c8c-105">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="85c8c-105">A description of the error.</span></span> <span data-ttu-id="85c8c-106">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="85c8c-106">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="85c8c-107">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="85c8c-107">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="85c8c-108">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="85c8c-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" /> class with the message string containing the device identifier that could not be found.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMessageLockLostException (string deviceId, Guid messageId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, valuetype System.Guid messageId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, messageId As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException : string * Guid -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException (deviceId, messageId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="messageId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="85c8c-109">Gerätebezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c8c-109">Device identifier.</span></span></param>
        <param name="messageId"><span data-ttu-id="85c8c-110">Der Meldungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c8c-110">Message identifier.</span></span></param>
        <summary>
            <span data-ttu-id="85c8c-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="85c8c-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" /> class with the message string containing the device identifier that could not be found.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>