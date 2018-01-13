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
            Die Ausnahme, die ausgelöst wird, wenn der Versuch, in die Warteschlange einreihen einer Nachricht fehlschlägt, weil die Nachrichtenwarteschlange für das Gerät bereits voll ist.
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
        <param name="maximumQueueDepth">Maximale Anzahl der Nachrichten in der Warteschlange.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> Klasse mit der Meldungszeichenfolge, die den Bezeichner des bereits vorhandenen Geräts enthält.
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
        <param name="message">Eine Beschreibung des Fehlers. Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein. Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter.
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
        <param name="message">Eine Beschreibung des Fehlers. Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein. Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</param>
        <param name="innerException">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>