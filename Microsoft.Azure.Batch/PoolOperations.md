<Type Name="PoolOperations" FullName="Microsoft.Azure.Batch.PoolOperations">
  <TypeSignature Language="C#" Value="public class PoolOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type PoolOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Führt die Pool-bezogenen Vorgänge auf Azure Batch-Konto.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ChangeOSVersion">
      <MemberSignature Language="C#" Value="public void ChangeOSVersion (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ChangeOSVersion(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersion(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ChangeOSVersion (poolId As String, targetOSVersion As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersion : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ChangeOSVersion (poolId, targetOSVersion, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="targetOSVersion">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ändert die Betriebssystemversion des angegebenen Pools.
            </summary>
        <remarks>
          <para>Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.  Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.  Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</para>
          <para>Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</para>
          <para>Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.  Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</para>
          <para>Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern. Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeOSVersionAsync (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ChangeOSVersionAsync(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersionAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ChangeOSVersionAsync (poolId, targetOSVersion, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="targetOSVersion">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ändert die Betriebssystemversion des angegebenen Pools.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.  Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.  Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</para>
          <para>Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</para>
          <para>Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.  Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</para>
          <para>Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern. Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</para>
          <para>Vorgang zum Ändern des Version wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateComputeNodeUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser (string poolId, string computeNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser(string poolId, string computeNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreateComputeNodeUser(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateComputeNodeUser (poolId As String, computeNodeId As String) As ComputeNodeUser" />
      <MemberSignature Language="F#" Value="member this.CreateComputeNodeUser : string * string -&gt; Microsoft.Azure.Batch.ComputeNodeUser" Usage="poolOperations.CreateComputeNodeUser (poolId, computeNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens, in denen das Benutzerkonto, das erstellt wird.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> , eine neue Compute Knoten Benutzerkonto an, die noch nicht im Batch-Dienst vorhanden ist darstellt.
            </summary>
        <returns>Ein ungebundenes <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> , ein neues Benutzerkonto, das nicht mit dem Computeknoten hinzugefügt wurde darstellt.</returns>
        <remarks>Um den neuen Benutzer hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePool () As CloudPool" />
      <MemberSignature Language="F#" Value="member this.CreatePool : unit -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Instanz des CloudPool, die entfernt wird und keine Beziehung Konsistenz keinem Pool in der Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> , einen neuen Pool, der nicht mit dem Batch-Dienst hinzugefügt wurde darstellt.
            Um den Pool der Batch-Konto hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.CloudServiceConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.CloudServiceConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, cloudServiceConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.CloudServiceConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="virtualMachineSize">
            Die Größe der virtuellen Maschinen in den Pool.  Finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ für Größen. Batch unterstützt alle Azure-Cloud-Dienst-VM-Größen außer sind ExtraSmall, A1V2 und A2V2.</param>
        <param name="cloudServiceConfiguration">Die <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> für den Pool.</param>
        <param name="targetDedicatedComputeNodes">
            Die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.
            </param>
        <param name="targetLowPriorityComputeNodes">
            Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.
            Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.
            </param>
        <summary>
            Erstellt eine Instanz des CloudPool, die entfernt wird und keine Beziehung Konsistenz keinem Pool in der Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> , einen neuen Pool, der nicht mit dem Batch-Dienst hinzugefügt wurde darstellt.
            Um den Pool der Batch-Konto hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</returns>
        <remarks>
          <para>Informationen zum Azure-gastbetriebssystemfamilien finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/ </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.VirtualMachineConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.VirtualMachineConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, virtualMachineConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.VirtualMachineConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="virtualMachineSize">Die Größe der virtuellen Maschinen in den Pool. Https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ für Windows-Größen und https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ für Linux-Größen angezeigt.
            </param>
        <param name="virtualMachineConfiguration">Die <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> für den Pool.</param>
        <param name="targetDedicatedComputeNodes">
            Die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.
            </param>
        <param name="targetLowPriorityComputeNodes">
            Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.
            Wenn <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> werden weggelassen wird, müssen Sie festlegen, die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> Eigenschaften.
            </param>
        <summary>
            Erstellt eine Instanz des CloudPool, die entfernt wird und keine Beziehung Konsistenz keinem Pool in der Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> , einen neuen Pool, der nicht mit dem Batch-Dienst hinzugefügt wurde darstellt.
            Um den Pool der Batch-Konto hinzuzufügen, rufen <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.PoolOperations" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</para>
          <para>Änderungen werden in der Reihenfolge der Auflistung angewendet. Der letzte write Wins.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUser">
      <MemberSignature Language="C#" Value="public void DeleteComputeNodeUser (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteComputeNodeUser(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUser(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteComputeNodeUser (poolId As String, computeNodeId As String, userName As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUser : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteComputeNodeUser (poolId, computeNodeId, userName, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id der Compute-Knoten, von dem Sie das Benutzerkonto löschen möchten.</param>
        <param name="userName">Der Name des Benutzerkontos ein, das gelöscht werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht das angegebene Benutzerkonto aus dem angegebenen Computeknoten.
            </summary>
        <remarks>
          <para>Sie können die Löschen eines Benutzerkontos nur, wenn diese wird von einem Serverknoten die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteComputeNodeUserAsync (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteComputeNodeUserAsync(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUserAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteComputeNodeUserAsync (poolId, computeNodeId, userName, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id der Compute-Knoten, von dem Sie das Benutzerkonto löschen möchten.</param>
        <param name="userName">Der Name des Benutzerkontos ein, das gelöscht werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht das angegebene Benutzerkonto aus dem angegebenen Computeknoten.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Sie können die Löschen eines Benutzerkontos nur, wenn diese wird von einem Serverknoten die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</para>
          <para>Der Löschvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteNodeFile (poolId, computeNodeId, filePath, recursive, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="filePath">Der Pfad der zu löschenden Datei.</param>
        <param name="recursive">
            Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht die angegebene Datei aus dem angegebenen Computeknoten.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang.  Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteNodeFileAsync (poolId, computeNodeId, filePath, recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="filePath">Der Pfad der zu löschenden Datei.</param>
        <param name="recursive">
            Wenn die Datei-Path-Parameter ein Verzeichnis anstelle einer Datei darstellt, können Sie den Parameter optional, rekursive auf "true" Löschen des Verzeichnisses und aller Dateien und Unterverzeichnisse darin festlegen. Wenn rekursiv "false" ist das Verzeichnis muss leer sein, oder Löschvorgang fehl.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht die angegebene Datei aus dem angegebenen Computeknoten.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Der Löschvorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePool">
      <MemberSignature Language="C#" Value="public void DeletePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeletePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeletePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeletePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeletePool (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id der dem zu löschenden Ressourcenpools an.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Löscht den angegebenen Pool.
            </summary>
        <remarks>
          <para>Der Löschvorgang fordert, dass der Pool gelöscht werden.  Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.
            Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</para>
          <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeletePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DeletePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id der dem zu löschenden Ressourcenpools an.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht den angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Löschvorgang fordert, dass der Pool gelöscht werden.  Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.
            Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</para>
          <para>Der Löschvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public void DisableAutoScale (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableAutoScale(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScale(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableAutoScale (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScale : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableAutoScale (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Deaktiviert die automatische Skalierung für den angegebenen Pool.
            </summary>
        <remarks>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAutoScaleAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAutoScaleAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScaleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableAutoScaleAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DisableAutoScaleAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Deaktiviert die automatische Skalierung für den angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Deaktivierungsvorgang für die automatische Skalierung wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void DisableComputeNodeScheduling (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableComputeNodeScheduling(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeScheduling(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableComputeNodeScheduling (poolId As String, computeNodeId As String, disableComputeNodeSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption), Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeScheduling : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableComputeNodeScheduling (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="disableComputeNodeSchedulingOption">Gibt an, was mit den derzeit ausgeführten Tasks. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeSchedulingAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableComputeNodeSchedulingAsync (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="disableComputeNodeSchedulingOption">Gibt an, was mit den derzeit ausgeführten Tasks. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Dieser Vorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public void EnableAutoScale (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableAutoScale(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableAutoScale (poolId As String, Optional autoscaleFormula As String = null, Optional autoscaleEvaluationInterval As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableAutoScale (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="autoscaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <param name="autoscaleEvaluationInterval">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll. Der Standardwert beträgt 15 Minuten. Der minimal zulässige Wert beträgt 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ermöglicht die automatische Skalierung für den angegebenen Pool.
            </summary>
        <remarks>
          <para>Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird. Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</para>
          <para>Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAutoScaleAsync (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAutoScaleAsync(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScaleAsync : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableAutoScaleAsync (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EnableAutoScaleAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="autoscaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <param name="autoscaleEvaluationInterval">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll. Der Standardwert beträgt 15 Minuten. Der minimal zulässige Wert beträgt 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ermöglicht die automatische Skalierung für den angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird. Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</para>
          <para>Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</para>
          <para>Der Vorgang zum Aktivieren der automatischen Skalierung wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void EnableComputeNodeScheduling (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableComputeNodeScheduling(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableComputeNodeScheduling (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeScheduling : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableComputeNodeScheduling (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeSchedulingAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeSchedulingAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableComputeNodeSchedulingAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Dieser Vorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScale(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function EvaluateAutoScale (poolId As String, autoscaleFormula As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScale : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.AutoScaleRun" Usage="poolOperations.EvaluateAutoScale (poolId, autoscaleFormula, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="autoscaleFormula">Die Formel für den Pool ausgewertet werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für den angegebenen Pool Skalierung.  Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.
            </summary>
        <returns>Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für den angegebenen Pool.</returns>
        <remarks>
          <para>Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.  Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</para>
          <para>Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScaleAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;" Usage="poolOperations.EvaluateAutoScaleAsync (poolId, autoscaleFormula, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EvaluateAutoScaleAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="autoscaleFormula">Die Formel für den Pool ausgewertet werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für den angegebenen Pool Skalierung.  Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.
            </summary>
        <returns>Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für den angegebenen Pool.</returns>
        <remarks>
          <para>Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.  Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</para>
          <para>Die Evaluate-Vorgänge werden asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.PoolStatistics" Usage="poolOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Zusammenfassung lebensdauerstatistiken für alle Pools im aktuellen Konto abgerufen.  
            Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
            </summary>
        <returns>Die poolstatistiken der aggregierten.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;" Usage="poolOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Zusammenfassung lebensdauerstatistiken für alle Pools im aktuellen Konto abgerufen.
            Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
            </summary>
        <returns>Die poolstatistiken der aggregierten.</returns>
        <remarks>Der Abrufvorgang für die Statistik wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNode GetComputeNode (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNode GetComputeNode(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNode(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetComputeNode : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.ComputeNode" Usage="poolOperations.GetComputeNode (poolId, computeNodeId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool abgerufen.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft den angegebenen Computeknoten ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetComputeNodeAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.GetComputeNodeAsync (poolId, computeNodeId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool abgerufen.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen Computeknoten ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</returns>
        <remarks>Das Abrufen des Knotens wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="poolOperations.GetNodeFile (poolId, computeNodeId, filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="filePath">Der Pfad der Datei abgerufen werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft Informationen zu einer Datei auf einem Serverknoten an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.NodeFile" /> mit Informationen über die Datei und die zum Herunterladen der Datei verwendet werden können (siehe <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />).</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.GetNodeFileAsync (poolId, computeNodeId, filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="filePath">Der Pfad der Datei abgerufen werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft Informationen zu einer Datei auf einem Serverknoten an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.NodeFile" /> mit Informationen über die Datei und die zum Herunterladen der Datei verwendet werden können (siehe <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />).</returns>
        <remarks>Der Abrufvorgang für die Datei wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool GetPool (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool GetPool(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetPool : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.GetPool (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id der dem Pool abgerufen.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> mit Informationen zu dem angegebenen Azure Batch-Pool.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPoolAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.GetPoolAsync (poolId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetPoolAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id der dem Pool abgerufen.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.CloudPool" /> mit Informationen zu dem angegebenen Azure Batch-Pool.</returns>
        <remarks>Die Get-Pool-Vorgang wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpStream As Stream, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpStream, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</param>
        <param name="rdpStream">Die <see cref="T:System.IO.Stream" /> in dem Inhalt der RDP-Datei geschrieben wird.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft eine Datei (Remote Desktop Protocol, RDP) für den angegebenen Knoten ab.
            </summary>
        <remarks>
          <para>Diese Methode schließt nicht die <paramref name="rdpStream" /> Stream und setzt nicht die Position nach dem Schreiben.
            Der Verantwortung des Aufrufers den Stream geschlossen ist, oder um die Position zurückzusetzen, wenn erforderlich.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft. Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück. Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> muss verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpFileNameToCreate As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</param>
        <param name="rdpFileNameToCreate">Der Dateipfad, an dem die RDP-Datei erstellt werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft eine Remotedesktopprotokoll-Datei für den angegebenen Knoten ab.
            </summary>
        <remarks>
          <para>Wenn die Datei durch angegeben <paramref name="rdpFileNameToCreate" /> bereits vorhanden ist, wird Sie überschrieben.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft. Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück. Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> muss verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpStream, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</param>
        <param name="rdpStream">Die <see cref="T:System.IO.Stream" /> in dem Inhalt der RDP-Datei geschrieben wird.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft eine Datei (Remote Desktop Protocol, RDP) für den angegebenen Knoten ab.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Diese Methode schließt nicht die <paramref name="rdpStream" /> Stream und setzt nicht die Position nach dem Schreiben.
            Der Verantwortung des Aufrufers den Stream geschlossen ist, oder um die Position zurückzusetzen, wenn erforderlich.</para>
          <para>Der Abrufvorgang für RDP-Datei wird asynchron ausgeführt.</para>
          <para>Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft. Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück. Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> muss verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</param>
        <param name="rdpFileNameToCreate">Der Dateipfad, an dem die RDP-Datei erstellt werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft eine Remotedesktopprotokoll-Datei für den angegebenen Knoten ab.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn die Datei durch angegeben <paramref name="rdpFileNameToCreate" /> bereits vorhanden ist, wird Sie überschrieben.</para>
          <para>Der Abrufvorgang für RDP-Datei wird asynchron ausgeführt.</para>
          <para>Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> Eigenschaft. Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, Batch-Dienst 409 (Konflikt) zurück. Für Anwendungspools mit <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> -Eigenschaft, die neue Methode <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> muss verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemoteLoginSettings (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As RemoteLoginSettings" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettings : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.RemoteLoginSettings" Usage="poolOperations.GetRemoteLoginSettings (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RemoteLoginSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> Eigenschaft. Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, Batch-Dienst 409 (Konflikt) zurück. Für Anwendungspools mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> -Eigenschaft, eine der Methoden GetRDPFileAsync/GetRDPFile muss verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettingsAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;" Usage="poolOperations.GetRemoteLoginSettingsAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens für das Remote Desktop-Datei abgerufen werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Einstellungen für der Abrufvorgang-Remoteanmeldung wird asynchron ausgeführt.</para>
          <para>Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> Eigenschaft. Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, Batch-Dienst 409 (Konflikt) zurück. Für Anwendungspools mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> -Eigenschaft, eine der Methoden GetRDPFileAsync/GetRDPFile muss verwendet werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListComputeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListComputeNodes(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListComputeNodes : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.ListComputeNodes (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> des angegebenen Pools.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die asynchron oder synchron Auflisten von Computeknoten verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Knoten aus dem Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Knoten werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeAgentSkus : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;" Usage="poolOperations.ListNodeAgentSkus (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die Knoten-Agent-Sku-Werte von Batch-Dienst unterstützt. 
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Knotenwerten-Agent-Sku synchron oder asynchron verwendet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string poolId, string computeNodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.ListNodeFiles (poolId, computeNodeId, recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id des Serverknotens.</param>
        <param name="recursive">Bei "true", listet rekursiv alle Dateien auf dem Computeknoten. Wenn "false" listet nur die Dateien in das Stammverzeichnis der Compute-Knoten.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet Dateien auf den angegebenen Computeknoten.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Dateien asynchron oder synchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. die Daten einer Datei werden aus der Batch-Dienst abgerufen, nur, wenn die Auflistung aufgezählt wird.
            Datenabruf ist nicht atomaren; Dateidaten werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt; ListPools (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; ListPools(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPools : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.ListPools (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.CloudPool">Pools</see> in dem Batch-Konto.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Pools synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Pools aus dem Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Pools sind in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPoolUsageMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPoolUsageMetrics(System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPoolUsageMetrics : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;" Usage="poolOperations.ListPoolUsageMetrics (startTime, endTime, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime">Die Startzeit des aggregationsintervalls durch diesen Eintrag abgedeckt werden.</param>
        <param name="endTime">Die Endzeit des aggregationsintervalls für diesen Eintrag.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die Nutzungsdaten Pool.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Metriken synchron oder asynchron verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Metrikdaten aus der Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Metrikdaten werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public void Reboot (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reboot(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reboot(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reboot (poolId As String, computeNodeId As String, Optional rebootOption As Nullable(Of ComputeNodeRebootOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reboot : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reboot (poolId, computeNodeId, rebootOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id der Serverknoten neu starten.</param>
        <param name="rebootOption">Gibt an, wann der Knoten neu starten und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Startet die angegebene Serverknoten neu.
            </summary>
        <remarks>
          <para>Sie können einen Serverknoten neu starten, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RebootAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RebootAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RebootAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RebootAsync (poolId, computeNodeId, rebootOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id der Serverknoten neu starten.</param>
        <param name="rebootOption">Gibt an, wann der Knoten neu starten und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Startet die angegebene Serverknoten neu.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Sie können einen Serverknoten neu starten, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</para>
          <para>Die Neustart-Vorgänge werden asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reimage(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reimage(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage (poolId As String, computeNodeId As String, Optional reimageOption As Nullable(Of ComputeNodeReimageOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reimage : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reimage (poolId, computeNodeId, reimageOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id der Serverknoten zum reimaging.</param>
        <param name="reimageOption">Gibt an, wann den Knoten ein reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.
            </summary>
        <remarks>
          <para>Compute-Knoten können erstellt werden, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReimageAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReimageAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ReimageAsync (poolId, computeNodeId, reimageOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die Id des Pools, den Compute-Knoten enthält.</param>
        <param name="computeNodeId">Die Id der Serverknoten zum reimaging.</param>
        <param name="reimageOption">Gibt an, wann den Knoten ein reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Compute-Knoten können erstellt werden, nur, wenn es in ist die <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> oder <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> Zustand.</para>
          <para>Das reimaging-Vorgänge werden asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNode">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.
            </summary>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodes As IEnumerable(Of ComputeNode), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodes">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus dem angegebenen Pool.
            </summary>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeIds As IEnumerable(Of String), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeIds">Die Ids der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus dem angegebenen Pool.
            </summary>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.
            </summary>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNode">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveFromPoolAsync (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Entfernt den angegebenen Compute-Knoten aus dem angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;RemoveFromPoolAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodes">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus dem angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="computeNodeIds">Die Ids der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus dem angegebenen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus einem Pool AllocationState des Pools ändert sich von gleichmäßig auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePool">
      <MemberSignature Language="C#" Value="public void ResizePool (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResizePool(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePool(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResizePool (poolId As String, Optional targetDedicatedComputeNodes As Nullable(Of Integer) = null, Optional targetLowPriorityComputeNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ResizePool : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ResizePool (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="targetDedicatedComputeNodes">
            Die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="targetLowPriorityComputeNodes">
            Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="resizeTimeout">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool. Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet. Der Standardwert ist 15 Minuten.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Ändert die Größe des angegebenen Pools.
            </summary>
        <remarks>
          <para>Die Größenänderung fordert, dass der Pool Größe geändert werden.  Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.
            Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</para>
          <para>
            Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").
            Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.  Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.
            </para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResizePoolAsync (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResizePoolAsync(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResizePoolAsync : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ResizePoolAsync (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="targetDedicatedComputeNodes">
            Die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="targetLowPriorityComputeNodes">
            Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="resizeTimeout">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool. Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet. Der Standardwert ist 15 Minuten.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ändert die Größe des angegebenen Pools.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Die Größenänderung fordert, dass der Pool Größe geändert werden.  Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.
            Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</para>
          <para>
            Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").
            Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.  Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.
            </para>
          <para>Die Größenänderung wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePool">
      <MemberSignature Language="C#" Value="public void StopResizePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void StopResizePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopResizePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.StopResizePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.StopResizePool (poolId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <summary>
            Beendet einen Pool Größenänderungsvorgangs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.  Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.  Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            </para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopResizePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopResizePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopResizePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.StopResizePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des Pools.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Beendet einen Pool Größenänderungsvorgangs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.  Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.  Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            </para>
          <para>Zum Beenden der Größe Vorgang führt asynchron aus.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>