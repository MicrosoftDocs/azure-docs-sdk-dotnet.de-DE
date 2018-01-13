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
            Die Ausnahme, die ausgelöst wird, wenn ein Versuch zur Kommunikation mit einem Gerät fehlschlägt, da das Sperrtoken unterbrochen wurde (wenn die Verbindung verloren geht und des z. B. wiedererlangen). Dieses Timeout hat dieselbe Wirkung, als ob die Nachricht Abandonned war.
            </summary>
    <remarks>
            Fehlermeldung abgebrochen werden erneut in die Warteschlange eingereihten in der Warteschlange pro Gerät und der <see cref="T:Microsoft.Azure.Devices.Client.DeviceClient" /> Instanz erneut empfangen. Eine abgelehnte Nachricht wird aus der Warteschlange gelöscht und nicht erneut vom Gerät empfangen wurden.
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
        <param name="message">Eine Beschreibung des Fehlers. Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein. Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.
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
        <param name="deviceId">Gerätebezeichner.</param>
        <param name="messageId">Der Meldungsbezeichner.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMessageLockLostException" /> Klasse bei der die Meldungszeichenfolge, enthält die Geräte-ID, die nicht gefunden wurde.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>