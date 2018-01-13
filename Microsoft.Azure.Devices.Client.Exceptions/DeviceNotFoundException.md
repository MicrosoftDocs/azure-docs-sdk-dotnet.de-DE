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
            Die Ausnahme, die ausgelöst wird, wenn ein Versuch zur Kommunikation mit einem Gerät fehlschlägt, da die angegebenen Geräte-ID nicht gefunden werden kann.
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
        <param name="deviceId">Gerätebezeichner, die bereits vorhanden ist.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.
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
        <param name="info">Ein Objekt, das die serialisierten Objektdaten zur ausgelösten Ausnahme enthält.</param>
        <param name="context">Ein Objekt, das Kontextinformationen zur Quelle bzw. zum Ziel enthält.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> -Klasse mit den angegebenen Serialisierungs- und Kontextinformationen.
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
        <param name="message">Eine Beschreibung des Fehlers. Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein. Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</param>
        <param name="innerException">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse mit der Zeichenfolge enthält den Bezeichner des Geräts, die nicht gefunden wurde und ein Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
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
        <param name="deviceId">Gerätebezeichner, die bereits vorhanden ist.</param>
        <param name="iotHubName">Der Name der IOT Hub-Instanz.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID und den IoT Hub-Instanz, die nicht gefunden wurde.
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
        <param name="deviceId">Gerätebezeichner, die bereits vorhanden ist.</param>
        <param name="iotHubName">Der Name der IOT Hub-Instanz.</param>
        <param name="trackingId">Nachverfolgen von Bezeichner, der für Zwecke der Telemetrie verwendet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceNotFoundException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>