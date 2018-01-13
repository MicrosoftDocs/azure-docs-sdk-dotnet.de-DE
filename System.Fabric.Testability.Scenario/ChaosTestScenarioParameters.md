<Type Name="ChaosTestScenarioParameters" FullName="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters">
  <TypeSignature Language="C#" Value="public class ChaosTestScenarioParameters : System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ChaosTestScenarioParameters extends System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ChaosTestScenarioParameters&#xA;Inherits TestScenarioParameters" />
  <TypeSignature Language="F#" Value="type ChaosTestScenarioParameters = class&#xA;    inherit TestScenarioParameters" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenarioParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This class is deprecated. Please use System.Fabric.Chaos.DataStructures.ChaosParameters instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Diese Klasse definiert die Testparameter zum Konfigurieren der ChaosTestScenario.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosTestScenarioParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.ChaosTestScenarioParameters : TimeSpan * int64 * bool * TimeSpan -&gt; System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" Usage="new System.Fabric.Testability.Scenario.ChaosTestScenarioParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun)" />
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
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">Die Höchstmenge des Wartezeit für den gesamten Cluster stabilisiert nach einer Iteration Fehler, bevor der Test fehlschlägt.</param>
        <param name="maxConcurrentFaults">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1. Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen. 2 oder 3 für diese Verwendung wird empfohlen.</param>
        <param name="enableMoveReplicaFaults">Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.</param>
        <param name="timeToRun"></param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" />-Klasse.</para>
        </summary>
        <returns>Das Objekt, das die Chaos Szenario Parameter typisiert als ChaosScenarioParameters enthält</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxClusterStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxClusterStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxClusterStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.MaxClusterStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxClusterStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxClusterStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.MaxClusterStabilizationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
    <Member MemberName="WaitTimeBetweenIterations">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenIterations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenIterations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.WaitTimeBetweenIterations" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenIterations As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenIterations : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.WaitTimeBetweenIterations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
  </Members>
</Type>