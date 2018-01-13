<Type Name="IotHubNotFoundException" FullName="Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException">
  <TypeSignature Language="C#" Value="public class IotHubNotFoundException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit IotHubNotFoundException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubNotFoundException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type IotHubNotFoundException = class&#xA;    inherit IotHubException" />
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
            Die Ausnahme, die ausgelöst wird, wenn die IoT Hub-Instanz nicht gefunden wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubNotFoundException (string iotHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string iotHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (iotHubName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException iotHubName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="iotHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="iotHubName">IoT Hub-Name, der nicht gefunden werden konnte.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException" /> Klasse bei der die Meldungszeichenfolge, die mit dem Namen der IoT Hub-Instanz, die nicht gefunden werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubNotFoundException (string iotHubName, string trackingId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string iotHubName, string trackingId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (iotHubName As String, trackingId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException : string * string -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException (iotHubName, trackingId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="iotHubName" Type="System.String" />
        <Parameter Name="trackingId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="iotHubName">IoT Hub-Name, der nicht gefunden werden konnte.</param>
        <param name="trackingId">Im Bezeichner für die Telemetrie nachverfolgen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubNotFoundException" /> Klasse bei der die Meldungszeichenfolge, die mit dem Namen der IoT Hub-Instanz, die nicht gefunden werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>