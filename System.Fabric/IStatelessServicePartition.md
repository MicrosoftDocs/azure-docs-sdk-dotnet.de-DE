<Type Name="IStatelessServicePartition" FullName="System.Fabric.IStatelessServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatelessServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatelessServicePartition = interface&#xA;    interface IServicePartition" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IServicePartition</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Stellt eine Partition, die einer zustandslosen Dienstinstanz zugeordnet ist.</para>
    </summary>
    <remarks>
      <para>Bereitgestellt, um eines zustandslosen Diensts als Parameter an die <see cref="T:System.Fabric.IServicePartition" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</param>
        <summary>
            Meldet Zustandsinformationen für die aktuelle statusfreien Dienstinstanz der Partition an. 
            </summary>
        <returns />
        <remarks>
          <para>Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.
            Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.
            Wenn der Bericht hohen Priorität verfügt, können Sie angeben, dass Sendeoptionen an, es sofort senden <see cref="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.
            </para>
          <para>Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , beschreibt die Berichtsinformationen Integrität z. B. Quelle, der Eigenschaft und der Integrität.</param>
        <param name="sendOptions">
          <para>Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Bericht gesendet wird.</para>
        </param>
        <summary>
            Meldet Zustandsinformationen für die aktuelle statusfreien Dienstinstanz der Partition an. 
            </summary>
        <returns />
        <remarks>
          <para>Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.
            Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.
            Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).
            Wenn der Bericht hohen Priorität verfügt, können Sie die Sendeoptionen sofort senden angeben.
            </para>
          <para>Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>