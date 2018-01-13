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
            <span data-ttu-id="7f65d-101">Diese Klasse definiert die Testparameter zum Konfigurieren der ChaosTestScenario.</span><span class="sxs-lookup"><span data-stu-id="7f65d-101">This class defines all the test parameters to configure the ChaosTestScenario.</span></span>
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
        <param name="maxClusterStabilizationTimeout"><span data-ttu-id="7f65d-102">Die Höchstmenge des Wartezeit für den gesamten Cluster stabilisiert nach einer Iteration Fehler, bevor der Test fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="7f65d-102">The maximum amount of time to wait for the entire cluster to stabilize after a fault iteration before failing the test.</span></span></param>
        <param name="maxConcurrentFaults"><span data-ttu-id="7f65d-103">Maximale Anzahl von gleichzeitigen Fehlern, die pro Iteration mit der niedrigsten induziert wird 1.</span><span class="sxs-lookup"><span data-stu-id="7f65d-103">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="7f65d-104">Je höher die aggressivere Parallelität die Failover ratenbasierte somit komplexere Serie von Fehlern, um Fehler zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="7f65d-104">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="7f65d-105">2 oder 3 für diese Verwendung wird empfohlen.</span><span class="sxs-lookup"><span data-stu-id="7f65d-105">using 2 or 3 for this is recommended.</span></span></param>
        <param name="enableMoveReplicaFaults"><span data-ttu-id="7f65d-106">Aktiviert oder deaktiviert die MovePrimary und MoveSecondary-Fehler.</span><span class="sxs-lookup"><span data-stu-id="7f65d-106">Enables or disables the MovePrimary and MoveSecondary faults.</span></span></param>
        <param name="timeToRun"></param>
        <summary>
          <para><span data-ttu-id="7f65d-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f65d-107">Initializes a new instance of the <see cref="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" /> class.</span></span></para>
        </summary>
        <returns><span data-ttu-id="7f65d-108">Das Objekt, das die Chaos Szenario Parameter typisiert als ChaosScenarioParameters enthält</span><span class="sxs-lookup"><span data-stu-id="7f65d-108">The object containing the Chaos scenario parameters, typed as ChaosScenarioParameters</span></span></returns>
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
            <span data-ttu-id="7f65d-109">Die Höchstmenge des Wartezeit für den Cluster stabilisiert nach einem Fehler, bevor der Test fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="7f65d-109">The maximum amount of time to wait for the cluster to stabilize after a fault before failing the test.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7f65d-110">Nach jeder Iteration wartet der ChaosTestScenario höchstens dieser Zeitspanne für den Cluster fehlerfrei sind</span><span class="sxs-lookup"><span data-stu-id="7f65d-110">After each iteration, the ChaosTestScenario waits for at most this amount of time for the cluster to become healthy</span></span>
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
            <span data-ttu-id="7f65d-111">Die Wartezeit zwischen zwei Iterationen für eine zufällige Dauer, die von diesem Wert gebunden.</span><span class="sxs-lookup"><span data-stu-id="7f65d-111">Wait time between two iterations for a random duration bound by this value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7f65d-112">Die Time-Trennung zwischen zwei aufeinander folgenden Iterationen der ChaosTestScenario</span><span class="sxs-lookup"><span data-stu-id="7f65d-112">The time-separation between two consecutive iterations of the ChaosTestScenario</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>