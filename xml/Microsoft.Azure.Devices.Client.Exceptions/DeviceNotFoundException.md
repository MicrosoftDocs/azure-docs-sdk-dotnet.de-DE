<Type Name="DeviceNotFoundException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException">
  <TypeSignature Language="C#" Value="public sealed class DeviceNotFoundException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit DeviceNotFoundException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceNotFoundException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceNotFoundException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="80e1c-101">Die Ausnahme, die ausgelöst wird, wenn ein Versuch zur Kommunikation mit einem Gerät fehlschlägt, da die angegebenen Geräte-ID nicht gefunden werden kann.</span><span class="sxs-lookup"><span data-stu-id="80e1c-101">The exception that is thrown when an attempt to communicate with a device fails because the given device identifier cannot be found.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceNotFoundException (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException deviceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="80e1c-102">Gerätebezeichner, die bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="80e1c-102">Device identifier that already exists.</span></span></param>
        <summary>
            <span data-ttu-id="80e1c-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="80e1c-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> class with the message string containing the device identifier that could not be found.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceNotFoundException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="80e1c-104">Ein Objekt, das die serialisierten Objektdaten zur ausgelösten Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="80e1c-104">An object that holds the serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="80e1c-105">Ein Objekt, das Kontextinformationen zur Quelle bzw. zum Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="80e1c-105">An object that contains contextual information about the source or destination.</span></span></param>
        <summary>
            <span data-ttu-id="80e1c-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> -Klasse mit den angegebenen Serialisierungs- und Kontextinformationen.</span><span class="sxs-lookup"><span data-stu-id="80e1c-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> class with the specified serialization and context information.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceNotFoundException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="80e1c-107">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="80e1c-107">A description of the error.</span></span> <span data-ttu-id="80e1c-108">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="80e1c-108">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="80e1c-109">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="80e1c-109">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="80e1c-110">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="80e1c-110">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="80e1c-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse mit der Zeichenfolge enthält den Bezeichner des Geräts, die nicht gefunden wurde und ein Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="80e1c-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> class with the message string containing the identifier of the device that could not be found and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceNotFoundException (string deviceId, string iotHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, string iotHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, iotHubName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException : string * string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException (deviceId, iotHubName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="iotHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="80e1c-112">Gerätebezeichner, die bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="80e1c-112">Device identifier that already exists.</span></span></param>
        <param name="iotHubName"><span data-ttu-id="80e1c-113">Der Name der IOT Hub-Instanz.</span><span class="sxs-lookup"><span data-stu-id="80e1c-113">Name of the IOT Hub instance.</span></span></param>
        <summary>
            <span data-ttu-id="80e1c-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID und den IoT Hub-Instanz, die nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="80e1c-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> class with the message string containing the device identifier and the IoT hub instance that could not be found.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceNotFoundException (string deviceId, string iotHubName, string trackingId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, string iotHubName, string trackingId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, iotHubName As String, trackingId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException : string * string * string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException (deviceId, iotHubName, trackingId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="iotHubName" Type="System.String" />
        <Parameter Name="trackingId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="80e1c-115">Gerätebezeichner, die bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="80e1c-115">Device identifier that already exists.</span></span></param>
        <param name="iotHubName"><span data-ttu-id="80e1c-116">Der Name der IOT Hub-Instanz.</span><span class="sxs-lookup"><span data-stu-id="80e1c-116">Name of the IOT Hub instance.</span></span></param>
        <param name="trackingId"><span data-ttu-id="80e1c-117">Nachverfolgen von Bezeichner, der für Zwecke der Telemetrie verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="80e1c-117">Tracking identifier that is used for telemetry purposes.</span></span></param>
        <summary>
            <span data-ttu-id="80e1c-118">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="80e1c-118">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> class with the message string containing the device identifier that could not be found.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>