<Type Name="ChaosParameters" FullName="System.Fabric.Chaos.DataStructures.ChaosParameters">
  <TypeSignature Language="C#" Value="public class ChaosParameters : System.Fabric.ByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ChaosParameters extends System.Fabric.ByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ChaosParameters&#xA;Inherits ByteSerializable" />
  <TypeSignature Language="F#" Value="type ChaosParameters = class&#xA;    inherit ByteSerializable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ByteSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse definiert die Testparameter zum Konfigurieren der ChaosTestScenario.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />-Klasse.</para>
        </summary>
        <returns>Das Objekt, das die Chaos Szenario Parameter typisiert als ChaosScenarioParameters enthält</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (long maxConcurrentFaults, Nullable&lt;TimeSpan&gt; timeToRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxConcurrentFaults, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.Int64,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxConcurrentFaults As Long, Optional timeToRun As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : int64 * Nullable&lt;TimeSpan&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxConcurrentFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="timeToRun" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxConcurrentFaults">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen. 2 oder 3 für diese Verwendung wird empfohlen.</param>
        <param name="timeToRun">Die Gesamtzeit, die Chaos ausgeführt werden soll; maximal zulässige Wert ist TimeSpan.FromSeconds ("uint". "MaxValue")</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />-Klasse.</para>
        </summary>
        <returns>Das Objekt, das die Chaos Szenario Parameter typisiert als ChaosScenarioParameters enthält</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, Nullable&lt;TimeSpan&gt; timeToRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, Optional timeToRun As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * Nullable&lt;TimeSpan&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">Die Höchstmenge an Wartezeit für den gesamten Cluster nach einem Fehler Iteration stabilisiert; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="maxConcurrentFaults">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen. 2 oder 3 für diese Verwendung wird empfohlen.</param>
        <param name="enableMoveReplicaFaults">Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.</param>
        <param name="timeToRun">Die Gesamtzeit, die Chaos ausgeführt werden soll; maximal zulässige Wert ist TimeSpan.FromSeconds ("uint". "MaxValue")</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />-Klasse.</para>
        </summary>
        <returns>Das Objekt, das die Chaos Szenario Parameter typisiert als ChaosScenarioParameters enthält</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan, context As Dictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">Die Höchstmenge an Wartezeit für den gesamten Cluster nach einem Fehler Iteration stabilisiert; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="maxConcurrentFaults">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen. 2 oder 3 für diese Verwendung wird empfohlen.</param>
        <param name="enableMoveReplicaFaults">Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.</param>
        <param name="timeToRun">Nach der Ausführung für diesen viel Zeit, hält Chaos; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="context">Dies ist eine Sammlung von (Schlüssel, Wert) Paare. Dies kann verwendet werden, zum Aufzeichnen von ausführlichen Kontext zu Warum Chaos z. B. gestartet wird.</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />-Klasse.</para>
        </summary>
        <returns>Das Objekt, das die Chaos Szenario Parameter typisiert als ChaosScenarioParameters enthält</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context, TimeSpan waitTimeBetweenIterations, TimeSpan waitTimeBetweenFaults);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context, valuetype System.TimeSpan waitTimeBetweenIterations, valuetype System.TimeSpan waitTimeBetweenFaults) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String},System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan, context As Dictionary(Of String, String), waitTimeBetweenIterations As TimeSpan, waitTimeBetweenFaults As TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; * TimeSpan * TimeSpan -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context, waitTimeBetweenIterations, waitTimeBetweenFaults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="waitTimeBetweenIterations" Type="System.TimeSpan" />
        <Parameter Name="waitTimeBetweenFaults" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">Die Höchstmenge an Wartezeit für den gesamten Cluster nach einem Fehler Iteration stabilisiert; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="maxConcurrentFaults">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen. 2 oder 3 für diese Verwendung wird empfohlen.</param>
        <param name="enableMoveReplicaFaults">Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.</param>
        <param name="timeToRun">Nach der Ausführung für diesen viel Zeit, hält Chaos; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="context">Dies ist eine Sammlung von (Schlüssel, Wert) Paare. Dies kann verwendet werden, zum Aufzeichnen von ausführlichen Kontext zu Warum Chaos z. B. gestartet wird.</param>
        <param name="waitTimeBetweenIterations">Dies ist die Zeitspanne zwischen zwei aufeinander folgenden Iterationen Fehler ratenbasierte anhalten. Die weitere der Pause, desto geringer ist die Rate der Fehler über einen Zeitraum; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="waitTimeBetweenFaults">Dies entspricht dem Umfang der Pause zwischen zwei aufeinander folgenden Fehler in einer einzelnen Iteration--die weitere der Pause, desto geringer die Parallelität von Fehlern; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context, TimeSpan waitTimeBetweenIterations, TimeSpan waitTimeBetweenFaults, System.Fabric.Health.ClusterHealthPolicy clusterHealthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context, valuetype System.TimeSpan waitTimeBetweenIterations, valuetype System.TimeSpan waitTimeBetweenFaults, class System.Fabric.Health.ClusterHealthPolicy clusterHealthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String},System.TimeSpan,System.TimeSpan,System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; * TimeSpan * TimeSpan * System.Fabric.Health.ClusterHealthPolicy -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context, waitTimeBetweenIterations, waitTimeBetweenFaults, clusterHealthPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="waitTimeBetweenIterations" Type="System.TimeSpan" />
        <Parameter Name="waitTimeBetweenFaults" Type="System.TimeSpan" />
        <Parameter Name="clusterHealthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">Die Höchstmenge an Wartezeit für den gesamten Cluster nach einem Fehler Iteration stabilisiert; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="maxConcurrentFaults">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen. 2 oder 3 für diese Verwendung wird empfohlen.</param>
        <param name="enableMoveReplicaFaults">Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.</param>
        <param name="timeToRun">Nach der Ausführung für diesen viel Zeit, hält Chaos; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="context">Dies ist eine Sammlung von (Schlüssel, Wert) Paare. Dies kann verwendet werden, zum Aufzeichnen von ausführlichen Kontext zu Warum Chaos z. B. gestartet wird.</param>
        <param name="waitTimeBetweenIterations">Dies ist die Zeitspanne zwischen zwei aufeinander folgenden Iterationen Fehler ratenbasierte anhalten. Die weitere der Pause, desto geringer ist die Rate der Fehler über einen Zeitraum; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="waitTimeBetweenFaults">Dies entspricht dem Umfang der Pause zwischen zwei aufeinander folgenden Fehler in einer einzelnen Iteration--die weitere der Pause, desto geringer die Parallelität von Fehlern; TimeSpan.FromSeconds ("uint". darf nicht überschreiten. "MaxValue")</param>
        <param name="clusterHealthPolicy">Die clusterintegritätsrichtlinie, die bestimmt, wie intakt ein Clusters in Chaos ratenbasierte Fehler gehen an sein muss.</param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.ClusterHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterHealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.ClusterHealthPolicy : System.Fabric.Health.ClusterHealthPolicy" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.ClusterHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ClusterHealthPolicy bestimmt den Zustand der Entitäten, die Chaos vor dem Wechseln in den nächsten Satz von Fehlern sichergestellt. "ConsiderWarningAsError" auf "false" festlegen würde ermöglichen, wechseln Sie auf den nächsten Satz von Fehlern, während mit "healthstate" im Cluster Entitäten sind Chaos == Warnung (obwohl Chaos Entitäten im Warnung beim Auswählen von faultable Entitäten übersprungen wird.)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; Context" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Context : System.Collections.Generic.Dictionary&lt;string, string&gt;" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sammlung von (Schlüssel, Wert)-Paaren, die während des Startens Chaos übergeben wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableMoveReplicaFaults">
      <MemberSignature Language="C#" Value="public bool EnableMoveReplicaFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableMoveReplicaFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.EnableMoveReplicaFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableMoveReplicaFaults As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableMoveReplicaFaults : bool with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.EnableMoveReplicaFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxClusterStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxClusterStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxClusterStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.MaxClusterStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxClusterStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxClusterStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.MaxClusterStabilizationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Höchstmenge des Wartezeit für den Cluster stabilisiert nach einem Fehler, bevor der Test fehlschlägt.
            </summary>
        <value>
            Nach jeder Iteration wartet der ChaosTestScenario höchstens dieser Zeitspanne für den Cluster fehlerfrei sind
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentFaults">
      <MemberSignature Language="C#" Value="public long MaxConcurrentFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.MaxConcurrentFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentFaults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentFaults : int64 with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.MaxConcurrentFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Die hohes Ergebnis der aggressivere Parallelität Failover; ratenbasierte komplexere Serie von Fehlern zum Aufdecken von Fehlern – mithilfe von 2 oder 3 dafür wird daher empfohlen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="chaosParameters.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br">Ein BinaryReader-Objekt</param>
        <summary>
            Liest den Status dieses Objekts aus Bytearray.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException">Das Ende des Streams erreicht ist. </exception>
        <exception cref="T:System.IO.IOException">Ein E/A-Fehler tritt auf. </exception>
      </Docs>
    </Member>
    <Member MemberName="TimeToRun">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToRun" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.TimeToRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToRun As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToRun : TimeSpan" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.TimeToRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Gesamtzeit für die das Szenario vor dem Beenden ausgeführt wird.
            </summary>
        <value>
            Gibt die maximale Laufzeit des Szenarios als TimeSpan
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosParameters.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolgendarstellung der-Klasse
            </summary>
        <returns>Ein String-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenFaults">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenFaults As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenFaults : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die maximale Wartezeit zwischen aufeinander folgenden Fehler: Je größer der Wert, desto niedriger die Parallelität (von Fehlern).
            </summary>
        <value>
            Gibt die maximale Wartezeit zwischen zwei aufeinander folgenden Fehler als ein TimeSpan-Objekt
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenIterations">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenIterations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenIterations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenIterations" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenIterations As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenIterations : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenIterations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Wartezeit zwischen zwei Iterationen für eine zufällige Dauer, die von diesem Wert gebunden.
            </summary>
        <value>
            Die Time-Trennung zwischen zwei aufeinander folgenden Iterationen der ChaosTestScenario
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="chaosParameters.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw">Ein BinaryWriter-Objekt.</param>
        <summary>
            Schreibt den Status dieses Objekts in ein Bytearray.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException">Ein E/A-Fehler tritt auf. </exception>
      </Docs>
    </Member>
  </Members>
</Type>