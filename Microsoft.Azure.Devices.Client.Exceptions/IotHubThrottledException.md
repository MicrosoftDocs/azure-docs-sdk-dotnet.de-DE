<Type Name="IotHubThrottledException" FullName="Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException">
  <TypeSignature Language="C#" Value="public sealed class IotHubThrottledException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit IotHubThrottledException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IotHubThrottledException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type IotHubThrottledException = class&#xA;    inherit IotHubException" />
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
            Die Ausnahme, die ausgelöst wird, wenn der Dienst exponential Backoff erfordert, da er die maximale Anzahl von zulässigen aktive Anforderungen überschritten hat.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubThrottledException (int maximumBatchCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maximumBatchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maximumBatchCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException : int -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException maximumBatchCount" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maximumBatchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maximumBatchCount">Maximale Anzahl der aktiven Anforderungen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" /> Klasse bei der die Meldungszeichenfolge, die die maximale Anzahl der aktiven Anforderungen enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubThrottledException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException (message, innerException)" />
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
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubThrottledException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>