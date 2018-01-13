<Type Name="ILeaseManager" FullName="Microsoft.Azure.EventHubs.Processor.ILeaseManager">
  <TypeSignature Language="C#" Value="public interface ILeaseManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILeaseManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILeaseManager" />
  <TypeSignature Language="F#" Value="type ILeaseManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Wenn Sie EventProcessorHost Leases an einer anderen Stelle als Azure-Speicher gespeichert haben möchten, können Sie eigene Verwendung dieser Schnittstelle Lease-Manager schreiben.  
            
            <para>Die Azure-Speicher-Manager verwenden den gleichen Speicher wie für Lease und Prüfpunkte, sodass beide Schnittstellen von derselben Klasse implementiert werden. Sie können dasselbe nicht tun, wenn Sie einheitlichen Speicher für beide Arten von Daten. </para> <para>Diese Schnittstelle nicht Initialisierungsmethoden angeben, da es keine Möglichkeit, zu wissen, welche Informationen, die Ihre Implementierung haben.</para></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; AcquireLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; AcquireLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.AcquireLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.AcquireLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">Lease-Informationen für die gewünschte Partition aus GetLeaseAsync() wie zuvor abgerufene</param>
        <summary>
            Die Lease für die gewünschte Partition für diese EventProcessorHost abrufen.
            
            <para>Beachten Sie, dass es zulässig ist, eine Lease abgerufen werden, die bereits von einem anderen Host gehört. Lease stehlen ist wie die Partitionen verteilt werden, wenn weitere Hosts gestartet werden.</para></summary>
        <returns>"true", wenn die Lease erfolgreich, "false" ist dies nicht eingerichtet wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseIfNotExistsAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.CreateLeaseIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">ID des zu erstellenden Lease-Informationen für die partition</param>
        <summary>
            Erstellen Sie im Store die Lease-Informationen für die angegebene Partition ist nicht vorhanden. Tun Sie nichts, wenn sie bereits im Speicher vorhanden ist. 
            </summary>
        <returns>die vorhandenen oder neu erstellten Lease-Informationen für die partition</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.CreateLeaseStoreIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Die Lease-Speicher erstellen, wenn sie nicht vorhanden ist, werden keine Aktionen ausgeführt, wenn er vorhanden ist.
            </summary>
        <returns>"true", wenn die Lease bereits speichern vorhanden oder wurde erfolgreich erstellt, "false" ist dies nicht der</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task" Usage="iLeaseManager.DeleteLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">Lease-Informationen für die gewünschte Partition aus GetLeaseAsync() wie zuvor abgerufene</param>
        <summary>
            Löschen Sie die Lease-Informationen für die angegebene Partition aus dem Speicher. Wenn keine gespeicherten Leasedauer für die angegebene Partition vorhanden ist, wird, erfolgreich behandelt.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseStoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteLeaseStoreAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteLeaseStoreAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseStoreAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteLeaseStoreAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseStoreAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.DeleteLeaseStoreAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            EventProcessorHost, aber eine praktische Funktion verwendet zum Testen haben nicht.
            </summary>
        <returns>True, wenn der Lease Speicher erfolgreich, "false" ist dies nicht der gelöscht wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLeases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetAllLeases" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLeases () As IEnumerable(Of Task(Of Lease))" />
      <MemberSignature Language="F#" Value="abstract member GetAllLeases : unit -&gt; seq&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;" Usage="iLeaseManager.GetAllLeases " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Geben Sie die Lease-Informationen für alle Partitionen zurück.
            Eine typische Implementierung aufrufen für alle Partitionen nur GetLeaseAsync().
            </summary>
        <returns>Liste der Lease-Informationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetLeaseAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLeaseAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member GetLeaseAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.GetLeaseAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">ID der Partition zum Abrufen der Lease für</param>
        <summary>
            Geben Sie die Lease-Informationen für die angegebene Partition zurück. Kann null zurück, wenn keine Lease im Speicher für die angegebene Partition erstellt wurde.
            </summary>
        <returns>Lease-Informationen für die Partition, oder null</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Meistens zum Testen hilfreich.
            </summary>
        <value>Die Dauer eines Lease, bevor es abläuft, es sei denn, erneuert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht eine Lease-Manager-Implementierung PartitionManager angeben, wie oft Leases überprüfen und erneuern, werden sollte. Um verteilen Leases rechtzeitig verarbeitet, nachdem ein Host wird nicht mehr funktioniert, empfiehlt es sich um einen relativ kurzen Intervall wie an den zehn Sekunden. Selbstverständlich sollte weniger als die Hälfte der Lease length-Funktion, um eine versehentliche Ablauf zu verhindern können.
            </summary>
        <value>Das Ruheintervall zwischen scans</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; LeaseStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; LeaseStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LeaseStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member LeaseStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.LeaseStoreExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ist der Lease-Speicher vorhanden?
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ReleaseLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ReleaseLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.ReleaseLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.ReleaseLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">Leasedauer zugewiesen werden, einrichten</param>
        <summary>
            Geben Sie auf eine Lease, die derzeit von diesem Host aufrecht erhalten.
            <para>Wenn die Lease, abgelaufen sind oder gestohlen wurden, freigegeben wurde, ist nicht erforderlich, und schlägt fehl, wenn versucht.</para></summary>
        <returns>"true", wenn die Lease erfolgreich, "false" ist dies nicht veröffentlicht wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RenewLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; RenewLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.RenewLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.RenewLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">Lease erneuert werden soll.</param>
        <summary>
            Erneuert eine Lease, die derzeit von diesem Host aufrecht erhalten.
            
            <para>Wenn die Lease wurde gestohlen wird oder abgelaufen oder freigegeben wurde, ist es nicht möglich, es zu erneuern. Sie müssen Sie getLease(), und klicken Sie dann acquireLease() erneut aufrufen.</para></summary>
        <returns>"true", wenn die Lease erfolgreich, "false" ist dies nicht der erneuert wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; UpdateLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; UpdateLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.UpdateLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member UpdateLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.UpdateLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">Neue Lease-Informationen gespeichert werden</param>
        <summary>
            Aktualisieren Sie den Store mit den Informationen in der angegebenen Lease an.
            
            <para>Es ist notwendig, eine Lease aktuell zu halten, um es zu aktualisieren. Wenn die Lease wurde gestohlen wird oder abgelaufen oder freigegeben wurde, kann er nicht aktualisiert werden. Aktualisieren von sollte die Lease verlängern, vor dem Ausführen der Update aus, um den Ablauf der Lease während des Prozesses zu vermeiden.</para></summary>
        <returns>"true", wenn die aktualisierte erfolgreich, "false" ist dies nicht ausgeführt wurde</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>