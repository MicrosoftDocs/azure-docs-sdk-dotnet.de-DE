<Type Name="FabricClient+FaultManagementClient" FullName="System.Fabric.FabricClient+FaultManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.FaultManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/FaultManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.FaultManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.FaultManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.FaultManagementClient = class" />
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
      <para>Stellt Funktionen zum Einfügen von Fehlern in einem Service Fabric-Cluster bereit.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="nodeName">Knoten zu benennen, wobei primären Replikat verschoben werden soll</param>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden. </param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>-API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">Knoten zu benennen, wobei primären Replikat verschoben werden soll</param>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden. </param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <summary>
             Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
             </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
             -API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.
             Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
             </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
             - Wenn die Aktion für statusfreien Dienst aufgerufen.
             - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Knoten zu benennen, wobei primären Replikat verschoben werden soll</param>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden. </param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
             Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
             </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
             -API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.
             Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
             </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
             - Wenn die Aktion für statusfreien Dienst aufgerufen.
             - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden. </param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            Diese Überladung verwendet zufälligen Knoten ausgewählt, die aus dem aktuellen Knoten aus, auf dem primäres Replikat nicht zum Zeitpunkt des API-Aufruf zum Verschieben von primären Replikats vorhanden ist.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.</remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Knoten zu benennen, wobei primären Replikat verschoben werden soll</param>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden. </param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
             Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
             </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
             -API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.
             Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
             </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
             - Wenn die Aktion für statusfreien Dienst aufgerufen.
             - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Knoten zu benennen, wobei primären Replikat verschoben werden soll</param>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.
            -API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            </param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Knoten zu benennen, wobei primären Replikat verschoben werden soll</param>
        <param name="partitionSelector">Verschieben von primären wird für diese Partition ausgewählt aufgerufen werden.
            -API verwendet das primäre Replikat der ausgewählten Partition an die neue Position verschoben.
            </param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte primäre Replikat zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit primären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das primäre Replikat der ausgewählten Partition an neue knotenspeicherort angegeben, indem Sie "nodename" verschieben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - primäres Replikat nicht bereit für das Verschieben von FabricErrorCode.AlreadyPrimaryReplica - ist wenn primäre Replikat für die ausgewählte Partition bereits vorhanden sein auf neue Knoten FabricErrorCode.ConstraintNotSatisfied - Wenn die Einschränkungen für die neue Ort des Replikats würde die Verschiebung nicht zulassen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.
            </param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das ausgewählte sekundäre Replikat in Partitionsstruktur-Selektor angegebene vom aktuellen sekundären Knoten. Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird. </param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das ausgewählte sekundäre Replikat in Partitionsstruktur-Selektor angegebene vom aktuellen sekundären Knoten. Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Replikat verschoben wird ist kein sekundärer FabricErrorCode.ConstraintNotSatisfied -, wenn die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>-API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur. Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            Diese Überladung API wählt nach dem Zufallsprinzip aktuellen sekundären Knoten für zufällige sekundäres Replikat der ausgewählten Partition und die neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Replikat verschoben wird ist kein sekundärer FabricErrorCode.ConstraintNotSatisfied -, wenn die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das nach dem Zufallsprinzip ausgewählte sekundäre Replikat für angegebene Partition-Auswahl.
            Diese Überladung API wählt zufallsgesteuert neuen sekundären knotenspeicherort für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>-API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur. Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Replikat verschoben wird ist kein sekundärer FabricErrorCode.ConstraintNotSatisfied -, wenn die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.
            </param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur. Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="newNodeName">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.
            </param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das nach dem Zufallsprinzip ausgewählte sekundäre Replikat für angegebene Partition-Auswahl.
            Diese Überladung API wählt zufallsgesteuert neuen sekundären knotenspeicherort für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das ausgewählte sekundäre Replikat in CurrentNodeName angegebene Partition-Selektor-Struktur. Diese Überladung API wählt nach dem Zufallsprinzip neuen sekundären Knoten für das Replikat verschieben, die dieser ausgewählte Replikat zum neuen knotenspeicherort aus der aktuellen Position verschoben wird.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>-API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben.
            Das ausgewählte Replikat wird an den nach dem Zufallsprinzip ausgewählten knotenspeicherort für neue verschoben werden.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="newNodeName">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="newNodeName">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>-API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben.
            Das ausgewählte Replikat wird an den nach dem Zufallsprinzip ausgewählten knotenspeicherort für neue verschoben werden.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="newNodeName">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            API verwendet das ausgewählte sekundäre Replikat durch CurrentNodeName angegeben und verschiebt sie in die neue Position von NewNodeName angegeben.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf den neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden, wenn aktives sekundäres Replikat für die ausgewählte Partition auf dem neuen Knoten vorhanden FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat kein sekundärer FabricErrorCode.ConstraintNotSatisfied - die Einschränkungen für den neuen Speicherort des Replikats das Verschieben nicht möglich ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="newNodeName">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das ausgewählte sekundäre Replikat in Selektor Partitionsstruktur nach CurrentNodeName Standort angegeben. Das ausgewählte Replikat wird in NewNodeName Speicherort aus der aktuellen Position verschoben werden.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">Name des Knotens, auf dem ausgewählten Replikat verschieben derzeit vorhanden ist.</param>
        <param name="newNodeName">Benennen Sie die Knoten ausgewählt Replikaten zu verschiebenden</param>
        <param name="partitionSelector">Verschieben Sie die sekundäre Datenbank auf dieser Partition ausgewählt aufgerufen wird.</param>
        <param name="ignoreConstraints">Ob Einschränkungen zu ignorieren, wenn versucht wird, der Verschiebevorgang auszuführen.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">das Abbruchtoken, das</param>
        <summary>
            Verschiebt die ausgewählte sekundäre Replikat vom aktuellen Knoten zum neuen Knoten im Cluster.
            </summary>
        <returns>Eine Aufgabe mit sekundären Ergebnis verschieben</returns>
        <remarks>
            -API verwendet das ausgewählte sekundäre Replikat in Selektor Partitionsstruktur nach CurrentNodeName Standort angegeben. Das ausgewählte Replikat wird in NewNodeName Speicherort aus der aktuellen Position verschoben werden.
            Diese API ist sicher d. h., dass es keine Quorum oder Datenverluste selbst entstehen, wenn zusätzliche Fehler oder Fehler zur gleichen Zeit auftreten.
            </remarks>
        <exception cref="T:System.TimeoutException">Versuchen Sie es erneut erschöpft ist.</exception>
        <exception cref="T:System.InvalidOperationException">Ungültiger Vorgang
            - Wenn die Aktion für statusfreien Dienst aufgerufen.
            - Wenn kein aktives sekundäres Replikat vorhanden ist.
            - Wenn nicht genügend Knoten, die für die Aktion verfügbar sind
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - primäres Replikat für die ausgewählte Partition bereits auf dem neuen Knoten FabricErrorCode.AlreadySecondaryReplica - vorhanden aktives sekundäres Replikat für die ausgewählte Partition bereits vorhanden für neue Knoten FabricErrorCode.InvalidReplicaStateForReplicaOperation - Wenn das Zielreplikat nicht mit einer sekundären Datenbank ist
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat entfernt werden soll.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der FM vie.w ist</param>
        <param name="forceRemove">Das Replikat wird erzwungen entfernt werden.</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat entfernt werden soll.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der Sicht FM ist</param>
        <param name="forceRemove">Das Replikat wird erzwungen entfernt werden.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat entfernt werden soll.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der Sicht FM ist.</param>
        <param name="forceRemove">Entfernt das Replikat erzwungen.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang, z. B. das Timeout für das Replikat entfernt werden soll, wenn warten <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">Name des Knotens, auf dem Replikat wird verschoben werden soll<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">Partitions-Id, in dem das Replikat muss entfernt werden </param>
        <param name="replicaId">Replikat-Id, die entfernt werden muss </param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <param name="forceRemove">Das Replikat wird erzwungen entfernt werden.</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Name des Knotens, auf dem Replikat wird verschoben werden soll<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">Partitions-Id, in dem das Replikat muss entfernt werden </param>
        <param name="replicaId">Replikat-Id, die entfernt werden muss </param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis das Entfernen des Replikats abgeschlossen ist oder nicht DoNotVerify - zurückgegebene nach dem Entfernen des Replikats Verify - Rückgabe nach Entfernen des Replikats also Abschluss auslösen, aus der Sicht FM ist.</param>
        <param name="forceRemove">Das Replikat wird erzwungen entfernt werden.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Name des Knotens, auf dem Replikat wird verschoben werden soll<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">Partitions-Id, in dem das Replikat muss entfernt werden </param>
        <param name="replicaId">Replikat-Id, die entfernt werden muss </param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <param name="forceRemove">Entfernt das Replikat erzwungen.</param>
        <param name="operationTimeoutSec">Das allgemeine Timeout in Sekunden für den Vorgang, z. B. das Timeout warten Replikat entfernt werden soll, wenn <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - dauerhaft) gemäß dem übergebenen entfernt in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RemoveReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> identifiziert das Replikat, dessen Codepaket Host muss neu gestartet werden.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <summary>
            Dieser API-Aufruf neu gestartet, wird das Codepaket hostet das Replikat gemäß der <see cref="T:System.Fabric.ReplicaSelector" /> und der angegebene Anwendungsname gehört.
            </summary>
        <returns>RestartDeployedCodePackageResult die Informationen zu den eigentlichen Codepaket neu gestartet und das Replikat ausgewählt haben.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist - Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde, – wenn die angegebene Partition ausgewählt nicht FabricErrorCode.CodePackageNotFound vorhanden ist – wenn die ausgewählten Code Paket wurde nicht gefunden.</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der Name der Anwendung zu dem Paket der Code belong.s</param>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> identifiziert das Replikat, dessen Codepaket Host muss neu gestartet werden.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Dieser API-Aufruf neu gestartet, wird das Codepaket hostet das Replikat gemäß der <see cref="T:System.Fabric.ReplicaSelector" /> und der angegebene Anwendungsname gehört.
            </summary>
        <returns>RestartDeployedCodePackageResult die Informationen zu den eigentlichen Codepaket neu gestartet und das Replikat ausgewählt haben.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist - Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde, – wenn die angegebene Partition ausgewählt nicht FabricErrorCode.CodePackageNotFound vorhanden ist – wenn die ausgewählten Code Paket wurde nicht gefunden.</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> identifiziert das Replikat, dessen Codepaket Host muss neu gestartet werden.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Code-Pakets abgeschlossen ist oder not.n</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang, z. B. das Timeout warten Codepaket wenn Neustart <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</param>
        <param name="token">Abbruchtoken.</param>
        <summary>
            Dieser API-Aufruf neu gestartet, wird das Codepaket hostet das Replikat gemäß der <see cref="T:System.Fabric.ReplicaSelector" /> und der angegebene Anwendungsname gehört.
            </summary>
        <returns>RestartDeployedCodePackageResult die Informationen zu den eigentlichen Codepaket neu gestartet und das Replikat ausgewählt haben.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist - Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde, – wenn die angegebene Partition ausgewählt nicht FabricErrorCode.CodePackageNotFound vorhanden ist – wenn die ausgewählten Code Paket wurde nicht gefunden.</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knoten, auf dem das Codepaket gehostet wird.</param>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="serviceManifestName">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</param>
        <param name="codePackageName">Der Name des Pakets Code neu gestartet werden</param>
        <param name="codePackageInstanceId">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <summary>
            Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.
            </summary>
        <returns>RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet. SelectedReplica ist keine in dieser Überladung.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knoten, auf dem das Codepaket gehostet wird</param>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="serviceManifestName">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist</param>
        <param name="codePackageName">Der Name des Pakets Code neu gestartet werden</param>
        <param name="codePackageInstanceId">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.
            </summary>
        <returns>RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet. SelectedReplica ist keine in dieser Überladung.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knoten, auf dem das Codepaket gehostet wird.</param>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="serviceManifestName">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</param>
        <param name="servicePackageActivationId">
          <para>
            Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> von bereitgestelltes Dienstpaket, die das Codepaket enthält. Sie erhalten die ServicePackageActivationId eines bereitgestellten Dienstpakets mit <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage. 
            </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </param>
        <param name="codePackageName">Der Name des Pakets Code neu gestartet werden</param>
        <param name="codePackageInstanceId">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <summary>
            Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.
            </summary>
        <returns>RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet. SelectedReplica ist keine in dieser Überladung.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knoten, auf dem das Codepaket gehostet wird.</param>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="serviceManifestName">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</param>
        <param name="codePackageName">Der Name des Pakets Code neu gestartet werden</param>
        <param name="codePackageInstanceId">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang, z. B. das Timeout warten Codepaket wenn Neustart <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.
            </summary>
        <returns>RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet. SelectedReplica ist keine in dieser Überladung.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knoten, auf dem das Codepaket gehostet wird</param>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="serviceManifestName">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist</param>
        <param name="servicePackageActivationId">
          <para>
            Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> von bereitgestelltes Dienstpaket, die das Codepaket enthält. Sie erhalten die ServicePackageActivationId eines bereitgestellten Dienstpakets mit <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage. 
            </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </param>
        <param name="codePackageName">Der Name des Pakets Code neu gestartet werden</param>
        <param name="codePackageInstanceId">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.
            </summary>
        <returns>RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet. SelectedReplica ist keine in dieser Überladung.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knoten, auf dem das Codepaket gehostet wird.</param>
        <param name="applicationName">Der Name der Anwendung, die das Codepaket angehört.</param>
        <param name="serviceManifestName">Der Name des im Dienstmanifest, in dem das Codepaket definiert ist.</param>
        <param name="servicePackageActivationId">
          <para>
            Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> von bereitgestelltes Dienstpaket, die das Codepaket enthält. Sie erhalten die ServicePackageActivationId eines bereitgestellten Dienstpakets mit <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage. 
            </para>
          <para>
            Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.
            Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.
            </para>
        </param>
        <param name="codePackageName">Der Name des Pakets Code neu gestartet werden</param>
        <param name="codePackageInstanceId">Die Code-Paket-Id für Codepaket mit dem ausgeführten das Wenn angegeben und nicht klicken Sie dann den Neustart entspricht nicht verarbeitet wird, wenn der Wert 0 wird der Vergleich wird übersprungen.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> die angibt, ob Sie warten, bis der Neustart des Pakets Code oder die nicht abgeschlossen wurde.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang, z. B. das Timeout warten Codepaket wenn Neustart <see cref="T:System.Fabric.CompletionMode" /> ist überprüfen</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Dieser API-Aufruf wird das Codepaket gemäß den Eingabeparametern neu gestartet.
            </summary>
        <returns>RestartDeployedCodePackageResult die enthält Informationen zu den eigentlichen Codepaket neu gestartet. SelectedReplica ist keine in dieser Überladung.</returns>
        <remarks>
            Die <see cref="T:System.Fabric.CompletionMode" /> Optionen sind DoNotVerify - Rückgabe nach dem Neustart des Pakets Code überprüfen - zurück, die nach der Neustart d. h. das Codepaket Abschluss auslösen wurde bereits wieder erneut.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.CodePackageNotFound – Wenn die ausgewählten Codepaket FabricErrorCode.InstanceIdMismatch nicht gefunden - Wenn die angegebene Instanz-Id stimmte nicht überein</exception>
        <exception cref="T:System.InvalidOperationException">Das Codepaket war nicht in einem gültigen ausgeführten Zustand.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.  Dieses Replikat entsprechenden Knoten werden neu gestartet werden.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.
              Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.
              Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.  Dieses Replikat entsprechenden Knoten werden neu gestartet werden.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.
              Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.
              Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens, neu zu starten.</param>
        <param name="nodeInstance">
          <para>Die Knoten-ID des Knotens, neu zu starten.
            Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.
            Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.
            Wenn die Instanz einen positiven Wert aufweist, wird er mit dem aktiven Knoten-ID verglichen.
            Wenn die IDs nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.
            Dieser Fehler kann durch eine veraltete Nachricht verursacht.
            </para>
        </param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.
              Wenn der Fehlercode NodeNotFound NodeName lautet oder NodeInstance ungültig ist.
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.
            Der Knoten, auf dem das Replikat bereitgestellt wird, wird neu gestartet werden.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.
              Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.
              Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens, neu zu starten.</param>
        <param name="nodeInstance">
          <para>Die Knoten-ID des Knotens, neu zu starten.
            Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.
            Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.
            Wenn die Instanz einen positiven Wert aufweist, wird er mit der aktiven Instanz-ID verglichen.
            Wenn die Instanzen nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.
            Dieser Fehler kann durch eine veraltete Nachricht verursacht.
            </para>
        </param>
        <param name="completionMode">Wenn auf festgelegt <see cref="F:System.Fabric.CompletionMode.Verify" />, das System überprüft, dass der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.
            Wenn auf festgelegt <see cref="F:System.Fabric.CompletionMode.DoNotVerify" />, die API gibt zurück, nachdem der Knoten Neustart initiiert wurde.</param>
        <param name="token">Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  Wenn ErrorCode NodeNotFound ist, ist der "nodename" ungültig.
            Wenn ErrorCode InstanceIdMismatch, ist die <paramref name="nodeInstance" /> bereitgestellten die gerade ausgeführte Instanz stimmt nicht überein.</exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartNodeAsync (nodeName As String, nodeInstance As BigInteger, operationTimeout As TimeSpan, token As CancellationToken) As Task(Of RestartNodeResult)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens, neu zu starten.</param>
        <param name="nodeInstance">
          <para>Die Knoten-ID des Knotens, neu zu starten.
            Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.
            Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.
            Wenn die Instanz einen positiven Wert aufweist, wird er mit dem aktiven Knoten-ID verglichen.
            Wenn die IDs nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.
            Dieser Fehler kann durch eine veraltete Nachricht verursacht.
            </para>
        </param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn ErrorCode NodeNotFound ist, ist der "nodename" ungültig.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Dieser Parameter wird verwendet, um ein bestimmtes Replikat auszuwählen.  Dieses Replikat entsprechenden Knoten werden neu gestartet werden.</param>
        <param name="createFabricDump"> Wenn auf True festgelegt, das System das Speicherabbild des Prozesses für Fabric.exe auf diesem Knoten erstellen.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die dem Zielknoten und das Replikat ausgewählt darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.
            Wenn der CreateFabricDump-Parameter festgelegt ist, beim Neustart des Prozesses abgestürzt ist, und das Absturzabbild befindet sich im Ordner Absturzabbilder, die die DCA hochladen konfiguriert werden können.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.
              Wenn der ErrorCode ReplicaDoesNotExist ist, wird das ausgewählte Replikat wurde nicht gefunden.
              Wenn der ErrorCode PartitionNotFound ist, wird die angegebene Partition ist nicht vorhanden.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens, neu zu starten.</param>
        <param name="nodeInstance">
          <para>Die Knoten-ID des Knotens, neu zu starten.
            Wenn nicht angegeben oder auf 0 festgelegt ist, wird der Wert ignoriert.
            Wenn die Instanz auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.
            Wenn die Instanz einen positiven Wert aufweist, wird er mit dem aktiven Knoten-ID verglichen.
            Wenn die IDs nicht übereinstimmen, wird der Prozess nicht neu gestartet, und ein Fehler auftritt.
            Dieser Fehler kann durch eine veraltete Nachricht verursacht.
            </para>
        </param>
        <param name="createFabricDump"> Wenn auf True festgelegt, das System das Speicherabbild des Prozesses für Fabric.exe auf diesem Knoten erstellen.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die der Knoten neu gestartet, und die API gibt bis NodeStatus verfügbar ist, und er hat nicht zurück.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten Neustart initiiert wurde.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Neustart ein Clusterknotens durch einen Neustart des Fabric.exe-Prozess, der der Knoten hostet.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>
            Diese API wird simuliert, Service Fabric-Knotenfehler im Cluster, der der Failover-Wiederherstellungspfaden Ihres Diensts getestet wird.
            </remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn ErrorCode NodeNotFound ist, ist der "nodename" ungültig.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat neu gestartet werden. Diese API kann nur für persistente dienstreplikate aufgerufen werden.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <summary>
            Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat neu gestartet werden. Diese API kann nur für persistente dienstreplikate aufgerufen werden.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen ReplicaSelector neu gestartet.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">Die <see cref="T:System.Fabric.ReplicaSelector" /> Dies bedeutet, dass das Replikat neu gestartet werden. Diese API kann nur für persistente dienstreplikate aufgerufen werden.</param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang, der das Timeout warten, bis Replikat neu gestartet werden, einschließlich <see cref="T:System.Fabric.CompletionMode" /> stellen Sie sicher ist.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Name des Knotens, auf dem Replikat muss neu gestartet werden<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">Partitions-Id, in dem das Replikat muss neu gestartet werden </param>
        <param name="replicaId">Replikat-Id, die neu gestartet werden muss </param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <summary>
            Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Name des Knotens, auf dem Replikat muss neu gestartet werden<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">Partitions-Id, in dem das Replikat muss neu gestartet werden </param>
        <param name="replicaId">Replikat-Id, die neu gestartet werden muss </param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen ReplicaSelector neu gestartet.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Name des Knotens, auf dem Replikat muss neu gestartet werden<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">Partitions-Id, in dem das Replikat muss neu gestartet werden </param>
        <param name="replicaId">Replikat-Id, die neu gestartet werden muss </param>
        <param name="completionMode">Die <see cref="T:System.Fabric.CompletionMode" /> , der angibt, ob Sie warten, bis der Neustart des Replikats abgeschlossen ist oder nicht DoNotVerify – nach dem Auslösen des Neustarts des Replikats Verify - zurück, nachdem das Entfernen abgeschlossen ist zurück</param>
        <param name="operationTimeoutSec">Das allgemeine Timeout in Sekunden für den Vorgang, der das Timeout warten, bis Replikat neu gestartet werden, einschließlich <see cref="T:System.Fabric.CompletionMode" /> stellen Sie sicher ist.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird neu gestartet, das Replikat (entspricht der ReportFault - temporäre) gemäß dem übergebenen in <see cref="T:System.Fabric.ReplicaSelector" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartReplicaResult ausgewählt Replikat.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.ReplicaDoesNotExist – Wenn das ausgewählte Replikat FabricErrorCode.PartitionNotFound nicht gefunden wurde - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu starten.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens, bevor er angehalten wurde. Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert. Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</param>
        <summary>
            Startet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.  
              Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu starten.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens, bevor er angehalten wurde.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Startet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.  
              Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu starten.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens, bevor er angehalten wurde.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="ipAddressOrFQDN">Die IP-Adresse oder den vollqualifizierten Domänennamen (FQDN des Zielknotens).  Wenn dieser Parameter angegeben wird, "ClusterConnectionPort" muss auch angegeben werden.  Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</param>
        <param name="clusterConnectionPort">Der Cluster Verbindungsport des Zielknotens.  Wenn dieser Parameter angegeben wird, muss auch "IpAddressOrFQDN" angegeben werden.  Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</param>
        <summary>
            Startet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.  
              Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu starten.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens, bevor er angehalten wurde.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="ipAddressOrFQDN">Die IP-Adresse oder den vollqualifizierten Domänennamen (FQDN des Zielknotens).  Wenn dieser Parameter angegeben wird, <paramref name="clusterConnectionPort" /> muss auch angegeben werden.  Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</param>
        <param name="clusterConnectionPort">Der Cluster Verbindungsport des Zielknotens.  Wenn dieser Parameter angegeben wird, <paramref name="ipAddressOrFQDN" /> muss auch angegeben werden.  Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Startet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.  
              Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StartNodeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu starten.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens, bevor er angehalten wurde.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="ipAddressOrFQDN">Die IP-Adresse oder den vollqualifizierten Domänennamen (FQDN des Zielknotens).  Wenn dieser Parameter angegeben wird, <paramref name="clusterConnectionPort" /> muss auch angegeben werden.  Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</param>
        <param name="clusterConnectionPort">Der Cluster Verbindungsport des Zielknotens.  Wenn dieser Parameter angegeben wird, <paramref name="ipAddressOrFQDN" /> muss auch angegeben werden.  Wenn keine Angabe gemacht wird, bestimmt das System intern diese.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten wurde gestartet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten-Start initiiert wurde.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das cancellationToken</param>
        <summary>
            Startet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn der Fehlercode Ungültiges Argument angezeigt, die "nodename lautet" oder NodeInstance ungültig ist.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.  
              Das ErrorCode ist NodeHasNotStoppedYet vorhanden, eine steht Beendigungsvorgang auf diesem Knoten.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu beenden.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens zu beenden.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten beendet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten beenden initiiert wurde.</param>
        <summary>
            Beendet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu beenden.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens zu beenden.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten beendet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten beenden initiiert wurde.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Beendet einen Clusterknoten an.
            </summary>
        <returns>Eine Aufgabe mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StopNodeAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname des Knotens zu beenden.</param>
        <param name="nodeInstance">Die Knoten-ID des Knotens zu beenden.  Wenn dies nicht angegeben oder auf 0 festgelegt ist, wird dies ignoriert.  Wenn dies auf-1 festgelegt ist, wird das System intern dieser Wert bestimmt.</param>
        <param name="completionMode">Wenn festgelegt, stellen Sie sicher, das System überprüft, die die Knoten beendet, und die API gibt nicht zurück, bis sie verfügt.  Wenn die API auf DoNotVerify festgelegt ist, zurückgegeben werden, wenn der Knoten beenden initiiert wurde.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das Abbruchtoken, das für alle Anforderungen zum Abbrechen des Vorgangs überwacht wird.</param>
        <summary>
            Beendet einen Clusterknoten an.
            </summary>
        <returns>Ein Task mit Informationen, die den Zielknoten darstellt.</returns>
        <remarks>Ein Clusterknoten ist ein Prozess, nicht um eine virtuelle oder physische Computer.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.  
              Wenn Sie die ErrorCode Ungültiges Argument angezeigt wird, ist "nodename" ungültig.  
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die gerade ausgeführte Instanz.
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
  </Members>
</Type>