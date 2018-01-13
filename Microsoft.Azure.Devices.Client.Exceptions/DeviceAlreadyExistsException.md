<Type Name="DeviceAlreadyExistsException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException">
  <TypeSignature Language="C#" Value="public sealed class DeviceAlreadyExistsException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit DeviceAlreadyExistsException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceAlreadyExistsException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceAlreadyExistsException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="5be47-101">Die Ausnahme, die ausgelöst wird, bei der Versuch, ein Gerät erstellen, da er bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5be47-101">The exception that is thrown when an attempt to create a device fails because it already exists.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAlreadyExistsException (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException deviceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="5be47-102">Gerätebezeichner, die bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5be47-102">Device identifier that already exists.</span></span></param>
        <summary>
            <span data-ttu-id="5be47-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> Klasse mit der Meldungszeichenfolge, die den Bezeichner des bereits vorhandenen Geräts enthält.</span><span class="sxs-lookup"><span data-stu-id="5be47-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> class with the message string containing the identifier of the already existing device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAlreadyExistsException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException (info, context)" />
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
        <param name="info"><span data-ttu-id="5be47-104">Ein Objekt, das die serialisierten Objektdaten zur ausgelösten Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="5be47-104">An object that holds the serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="5be47-105">Ein Objekt, das Kontextinformationen zur Quelle bzw. zum Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="5be47-105">An object that contains contextual information about the source or destination.</span></span></param>
        <summary>
            <span data-ttu-id="5be47-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> -Klasse mit den angegebenen Serialisierungs- und Kontextinformationen.</span><span class="sxs-lookup"><span data-stu-id="5be47-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> class with the specified serialization and context information.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAlreadyExistsException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="5be47-107">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="5be47-107">A description of the error.</span></span> <span data-ttu-id="5be47-108">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="5be47-108">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="5be47-109">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="5be47-109">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="5be47-110">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="5be47-110">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="5be47-111">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> Klasse mit die Meldungszeichenfolge auf die Geräte-ID des bereits vorhandenen Geräts und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="5be47-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceAlreadyExistsException" /> class with the message string set to the device identifier of the already existing device and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>