<Type Name="IServicePartition" FullName="System.Fabric.IServicePartition">
  <TypeSignature Language="C#" Value="public interface IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartition" />
  <TypeSignature Language="F#" Value="type IServicePartition = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public interface member from V1.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Enthält Informationen zum Dienst die Partition, zu der sie gehört, und bietet Methoden für den Dienst für die Interaktion mit dem System während der Laufzeit.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IServicePartition.PartitionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInfo As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInfo : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.IServicePartition.PartitionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ermöglicht den Zugriff auf die <see cref="T:System.Fabric.ServicePartitionInformation" /> des Diensts, enthält die Partitionstyp und -ID.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.ServicePartitionInformation" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportFault">
      <MemberSignature Language="C#" Value="public void ReportFault (System.Fabric.FaultType faultType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportFault(valuetype System.Fabric.FaultType faultType) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />
      <MemberSignature Language="F#" Value="abstract member ReportFault : System.Fabric.FaultType -&gt; unit" Usage="iServicePartition.ReportFault faultType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="faultType" Type="System.Fabric.FaultType" />
      </Parameters>
      <Docs>
        <param name="faultType">
          <para>Die <see cref="T:System.Fabric.FaultType" /> , die der Dienst aufgetreten sind.</para>
        </param>
        <summary>
          <para>Das Replikat für die Laufzeit einen Fehler melden können, und gibt an, dass er einen Fehler gestoßen ist, aus dem es wiederherstellen und neu gestartet oder entfernt werden müssen kann nicht.</para>
        </summary>
        <remarks>
          <para>Ein Fehler wird i. d. r. gemeldet, wenn der Dienstcode ein Problem festgestellt wird von dem es nicht wiederhergestellt werden kann.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportLoad">
      <MemberSignature Language="C#" Value="public void ReportLoad (System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportLoad(class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.LoadMetric&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportLoad (metrics As IEnumerable(Of LoadMetric))" />
      <MemberSignature Language="F#" Value="abstract member ReportLoad : seq&lt;System.Fabric.LoadMetric&gt; -&gt; unit" Usage="iServicePartition.ReportLoad metrics" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metrics" Type="System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="metrics">
          <para>Eine Auflistung von <see cref="T:System.Fabric.LoadMetric" /> um die Last zu melden. </para>
        </param>
        <summary>
          <para>Meldet die Last für einen Satz von Metriken für den Lastenausgleich. Die Auslastung kann zu einem beliebigen Zeitpunkt über gemeldet werden die <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" /> Methode und stellt eine oder mehrere Eigenschaften von der <see cref="T:System.Fabric.LoadMetric" /> Methode.</para>
        </summary>
        <remarks>
          <para>Sollte die gemeldeten Metriken entsprechen, auf die finden Sie in der <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> als Teil der <see cref="T:System.Fabric.Description.ServiceDescription" /> , die zum Erstellen des Diensts verwendet wird. Lastmetriken, die nicht in der Beschreibung vorhanden sind, werden ignoriert. Können benutzerdefinierte Metriken Reporting Service Fabric zum Lastenausgleich für Dienste, die zusätzliche benutzerdefinierte Informationen basieren.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportMoveCost">
      <MemberSignature Language="C#" Value="public void ReportMoveCost (System.Fabric.MoveCost moveCost);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportMoveCost(valuetype System.Fabric.MoveCost moveCost) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportMoveCost(System.Fabric.MoveCost)" />
      <MemberSignature Language="F#" Value="abstract member ReportMoveCost : System.Fabric.MoveCost -&gt; unit" Usage="iServicePartition.ReportMoveCost moveCost" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="moveCost" Type="System.Fabric.MoveCost" />
      </Parameters>
      <Docs>
        <param name="moveCost">
          <para>Die gemeldete <see cref="T:System.Fabric.MoveCost" />.</para>
        </param>
        <summary>
          <para>Meldet die Move-Kosten für ein Replikat.</para>
        </summary>
        <remarks>
          <para>Dienste können verschieben Kosten für ein Replikat, das mit dieser Methode gemeldet werden. Während der Service Fabric-Ressource Bilanzen den besten Kompromiss im Cluster sucht, überprüft es Informationen geladen und Kosten für jedes Replikat verschieben. Ressource Bilanzen, bevorzugen wahrscheinlich Replikate mit niedrigeren Kosten zu verschieben, um einen Lastenausgleich zu erzielen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iServicePartition.ReportPartitionHealth healthInfo" />
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
            Partitionsintegrität der aktuellen gemeldet. 
            </summary>
        <returns />
        <remarks>
          <para>Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.
            Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.
            Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).
            Wenn der Bericht hohen Priorität verfügt, können Sie angeben, dass Sendeoptionen an, es sofort senden <see cref="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.
            </para>
          <para>Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Dies gibt an, dass die Partitionsobjekt geschlossen ist. Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iServicePartition.ReportPartitionHealth (healthInfo, sendOptions)" />
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
          <para>Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Partition Bericht gesendet wird.</para>
        </param>
        <summary>
            Partitionsintegrität der aktuellen gemeldet. 
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