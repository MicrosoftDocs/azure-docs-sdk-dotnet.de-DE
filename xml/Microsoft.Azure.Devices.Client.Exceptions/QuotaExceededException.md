<Type Name="QuotaExceededException" FullName="Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException">
  <TypeSignature Language="C#" Value="public sealed class QuotaExceededException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit QuotaExceededException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QuotaExceededException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type QuotaExceededException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="43c4c-101">Die Ausnahme, die ausgelöst wird, wenn ein Versuch zum Hinzufügen eines Geräts fehlschlägt, da die maximale Anzahl der registrierten Geräte erreicht wurde.</span><span class="sxs-lookup"><span data-stu-id="43c4c-101">The exception that is thrown when an attempt to add a device fails because the maximum number of registered devices has been reached.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="43c4c-102">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="43c4c-102">A description of the error.</span></span> <span data-ttu-id="43c4c-103">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="43c4c-103">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="43c4c-104">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="43c4c-104">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="43c4c-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter.</span><span class="sxs-lookup"><span data-stu-id="43c4c-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" /> class with the message string set to the message parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="43c4c-106">Eine Beschreibung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="43c4c-106">A description of the error.</span></span> <span data-ttu-id="43c4c-107">Der Inhalt der Meldung soll in verständlicher Sprache gehalten sein.</span><span class="sxs-lookup"><span data-stu-id="43c4c-107">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="43c4c-108">Der Aufrufer dieses Konstruktors muss sicherstellen, dass diese Zeichenfolge für die aktuelle Systemkultur lokalisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="43c4c-108">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="43c4c-109">Die Ausnahme, die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="43c4c-109">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="43c4c-110">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" /> Klasse mit die Meldungszeichenfolge auf Message-Parameter und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="43c4c-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.QuotaExceededException" /> class with the message string set to the message parameter and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>