<Type Name="HealthReportSendOptions" FullName="System.Fabric.Health.HealthReportSendOptions">
  <TypeSignature Language="C#" Value="public sealed class HealthReportSendOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthReportSendOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthReportSendOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthReportSendOptions" />
  <TypeSignature Language="F#" Value="type HealthReportSendOptions = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="45629-101">Stellt die Sendeoptionen, die angewendet werden, beim Senden einer <see cref="T:System.Fabric.Health.HealthReport" />.</span><span class="sxs-lookup"><span data-stu-id="45629-101">Represents the send options that are applied when sending a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="45629-102">Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span><span class="sxs-lookup"><span data-stu-id="45629-102">The report can be sent to the health store using <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthReportSendOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthReportSendOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="45629-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthReportSendOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="45629-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> class.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="45629-104">Es werden standardmäßig keine Send-Optionen festgelegt.</span><span class="sxs-lookup"><span data-stu-id="45629-104">By default, there are no send options set.</span></span> <span data-ttu-id="45629-105">Die Fabric-Client Einstellungen verwendet werden, um zu bestimmen, wann den Bericht gesendet und wann wiederholen bei einem Fehler zu senden.</span><span class="sxs-lookup"><span data-stu-id="45629-105">The fabric client settings are used to determine when to send the report and when to retry send on failure.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Immediate">
      <MemberSignature Language="C#" Value="public bool Immediate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Immediate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthReportSendOptions.Immediate" />
      <MemberSignature Language="VB.NET" Value="Public Property Immediate As Boolean" />
      <MemberSignature Language="F#" Value="member this.Immediate : bool with get, set" Usage="System.Fabric.Health.HealthReportSendOptions.Immediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45629-106">Ruft ab oder legt das Flag, das angibt, ob der Bericht sofort gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="45629-106">Gets or sets the flag which indicates whether the report should be sent immediately.</span></span>
            <span data-ttu-id="45629-107">Der Standardwert ist "false", in dem Fall Bericht pro die Fabric-Clientintegrität gesendet wird gemeldet, verwandte Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="45629-107">Defaults to false, in which case the report is sent per the fabric client health report related settings.</span></span>
            </summary>
        <value><span data-ttu-id="45629-108">Ein Flag, das angibt, ob der Bericht sofort gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="45629-108">A flag which indicates whether the report should be sent immediately.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="45629-109">Wenn <languageKeyword>"true"</languageKeyword>, der Bericht wird sofort gesendet, unabhängig von der <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> Konfiguration auf dem Client Integritätsstatus festgelegt.</span><span class="sxs-lookup"><span data-stu-id="45629-109">If <languageKeyword>true</languageKeyword>, the report is sent immediately, regardless of the <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> configuration set on the health client.</span></span>
            <span data-ttu-id="45629-110">Dies ist hilfreich für kritische Berichte, die so bald wie möglich gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="45629-110">This is useful for critical reports that should be sent as soon as possible.</span></span>
            <span data-ttu-id="45629-111">Ein weiteres Szenario, in denen dies möglicherweise nützlich, ist, wenn der Client muss, z. B. geschlossen werden, da der Hostprozess wird heruntergefahren, und Sie erhöhen die Wahrscheinlichkeit des Berichts gesendet werden müssen.</span><span class="sxs-lookup"><span data-stu-id="45629-111">Another scenario where this may be useful is if the client needs to be closed, for example because the host process is going down, and you need to increase the chances of the report being sent.</span></span>
            <span data-ttu-id="45629-112">Abhängig von der zeitlichen Steuerung und andere Bedingungen möglicherweise Senden des Berichts dennoch fehlschlagen, da der Client keine Zeit zum Senden von vor dem Herunterfahren oder weil die Nachricht verloren gegangen ist und der Integrität Client ausgefallen, bevor wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="45629-112">Depending on timing and other conditions, sending the report may still fail, either because the client doesn't have time to send it before shutdown, or because the message is lost and the health client went down before it can retry.</span></span>
            </para>
          <para>
            <span data-ttu-id="45629-113">Wenn <languageKeyword>"false"</languageKeyword>, der Bericht wird gesendet basierend auf die Integrität-Clienteinstellungen, insbesondere die <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="45629-113">If <languageKeyword>false</languageKeyword>, the report is sent based on the health client settings, especially the <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> configuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="45629-114">Standardmäßig werden die Berichte nicht sofort gesendet.</span><span class="sxs-lookup"><span data-stu-id="45629-114">By default, reports are not sent immediately.</span></span>
            <span data-ttu-id="45629-115">Dies ist die empfohlene Einstellung, da den Integrität Client Nachrichten in Health Store sowie die Verarbeitung von integritätsberichten für Zustandsberichte optimieren können.</span><span class="sxs-lookup"><span data-stu-id="45629-115">This is the recommended setting because it allows the health client to optimize health reporting messages to health store as well as health report processing.</span></span> 
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>