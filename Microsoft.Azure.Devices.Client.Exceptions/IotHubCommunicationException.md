<Type Name="IotHubCommunicationException" FullName="Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException">
  <TypeSignature Language="C#" Value="public sealed class IotHubCommunicationException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit IotHubCommunicationException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IotHubCommunicationException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type IotHubCommunicationException = class&#xA;    inherit IotHubException" />
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
            Die Ausnahme, die ausgelöst wird, wenn ein Versuch, mit dem IoT Hub-Dienst kommunizieren fehlschlägt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubCommunicationException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException message" />
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
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubCommunicationException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException (message, innerException)" />
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
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>