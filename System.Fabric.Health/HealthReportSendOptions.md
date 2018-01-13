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
      <para>Stellt die Sendeoptionen, die angewendet werden, beim Senden einer <see cref="T:System.Fabric.Health.HealthReport" />.</para>
    </summary>
    <remarks>
      <para>Der Bericht kann gesendet werden, mit dem Health Store <see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />.</para>
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
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthReportSendOptions" />-Klasse.</para>
        </summary>
        <remarks>Es werden standardmäßig keine Send-Optionen festgelegt. Die Fabric-Client Einstellungen verwendet werden, um zu bestimmen, wann den Bericht gesendet und wann wiederholen bei einem Fehler zu senden.</remarks>
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
            Ruft ab oder legt das Flag, das angibt, ob der Bericht sofort gesendet werden soll.
            Der Standardwert ist "false", in dem Fall Bericht pro die Fabric-Clientintegrität gesendet wird gemeldet, verwandte Einstellungen.
            </summary>
        <value>Ein Flag, das angibt, ob der Bericht sofort gesendet werden soll.</value>
        <remarks>
          <para>
            Wenn <languageKeyword>"true"</languageKeyword>, der Bericht wird sofort gesendet, unabhängig von der <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> Konfiguration auf dem Client Integritätsstatus festgelegt.
            Dies ist hilfreich für kritische Berichte, die so bald wie möglich gesendet werden soll.
            Ein weiteres Szenario, in denen dies möglicherweise nützlich, ist, wenn der Client muss, z. B. geschlossen werden, da der Hostprozess wird heruntergefahren, und Sie erhöhen die Wahrscheinlichkeit des Berichts gesendet werden müssen.
            Abhängig von der zeitlichen Steuerung und andere Bedingungen möglicherweise Senden des Berichts dennoch fehlschlagen, da der Client keine Zeit zum Senden von vor dem Herunterfahren oder weil die Nachricht verloren gegangen ist und der Integrität Client ausgefallen, bevor wiederholt werden kann.
            </para>
          <para>
            Wenn <languageKeyword>"false"</languageKeyword>, der Bericht wird gesendet basierend auf die Integrität-Clienteinstellungen, insbesondere die <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> Konfiguration.
            </para>
          <para>
            Standardmäßig werden die Berichte nicht sofort gesendet.
            Dies ist die empfohlene Einstellung, da den Integrität Client Nachrichten in Health Store sowie die Verarbeitung von integritätsberichten für Zustandsberichte optimieren können. 
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>