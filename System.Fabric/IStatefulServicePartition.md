<Type Name="IStatefulServicePartition" FullName="System.Fabric.IStatefulServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatefulServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatefulServicePartition = interface&#xA;    interface IServicePartition" />
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
      <para>Stellt eine Partition, die eines zustandsbehafteten dienstreplikats zugeordnet ist. </para>
    </summary>
    <remarks>
      <para>Abgeleitet von <see cref="T:System.Fabric.IServicePartition" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReplicator">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricReplicator CreateReplicator (System.Fabric.IStateProvider stateProvider, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.FabricReplicator CreateReplicator(class System.Fabric.IStateProvider stateProvider, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member CreateReplicator : System.Fabric.IStateProvider * System.Fabric.ReplicatorSettings -&gt; System.Fabric.FabricReplicator" Usage="iStatefulServicePartition.CreateReplicator (stateProvider, replicatorSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricReplicator</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateProvider" Type="System.Fabric.IStateProvider" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="stateProvider">
          <para>Die <see cref="T:System.Fabric.IStateProvider" /> mit dem zurückgegebenen <see cref="T:System.Fabric.FabricReplicator" /> verknüpft werden sollen. Dies ist häufig das gleiche Objekt, das implementiert <see cref="T:System.Fabric.IStatefulServiceReplica" />, jedoch bestimmte Dienste möglicherweise anders behandelt werden. </para>
        </param>
        <param name="replicatorSettings">
          <para>Die <see cref="T:System.Fabric.ReplicatorSettings" /> mit dem zurückgegebenen <see cref="T:System.Fabric.FabricReplicator" /> muss konfiguriert werden. </para>
        </param>
        <summary>
          <para>Erstellt eine <see cref="T:System.Fabric.FabricReplicator" /> mit den angegebenen Einstellungen und gibt ihn an das Replikat zurück. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.FabricReplicator" />zurück.</para>
        </returns>
        <remarks>
          <para>Diese Methode sollte verwendet werden, zum Erstellen einer <see cref="T:System.Fabric.FabricReplicator" /> Service als die <see cref="T:System.Fabric.IStateReplicator" /> für ein zustandsbehafteter Dienst, der implementiert <see cref="T:System.Fabric.IStateProvider" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Verwendet, um die Bereitschaft des Replikats hinsichtlich Lesevorgänge zu überprüfen. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.PartitionAccessStatus" />zurück.</para>
        </value>
        <remarks>
          <para>Die <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> sollte aktiviert sein, bevor das Replikat eine kundenanforderung verarbeitet wird, die ein Lesevorgang ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth healthInfo" />
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
            Integrität für die aktuelle zustandsbehafteten dienstreplikats der Partition gemeldet.
            </summary>
        <returns />
        <remarks>
          <para>Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.
            Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.
            Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).
            Wenn der Bericht hohen Priorität verfügt, können Sie angeben, dass Sendeoptionen an, es sofort senden <see cref="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.
            </para>
          <para>Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth (healthInfo, sendOptions)" />
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
        <param name="healthInfo">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</param>
        <param name="sendOptions">
          <para>Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Bericht gesendet wird.</para>
        </param>
        <summary>
            Integrität für die aktuelle zustandsbehafteten dienstreplikats der Partition gemeldet.
            </summary>
        <returns />
        <remarks>
          <para>Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.
            Intern verwendet die Partition einen internen Health-Client zum Senden der Berichte im Health Store.
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
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Verwendet, um die Bereitschaft der Partition hinsichtlich Schreibvorgänge zu überprüfen. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.PartitionAccessStatus" />zurück.</para>
        </value>
        <remarks>
          <para>Die <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> sollte aktiviert sein, bevor das Replikat eine kundenanforderung Dienste, von denen ein Schreibvorgang ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>