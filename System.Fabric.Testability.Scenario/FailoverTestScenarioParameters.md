<Type Name="FailoverTestScenarioParameters" FullName="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters">
  <TypeSignature Language="C#" Value="public class FailoverTestScenarioParameters : System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FailoverTestScenarioParameters extends System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverTestScenarioParameters&#xA;Inherits TestScenarioParameters" />
  <TypeSignature Language="F#" Value="type FailoverTestScenarioParameters = class&#xA;    inherit TestScenarioParameters" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenarioParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse definiert die Testparameter zum Konfigurieren der FailoverTestScenario.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverTestScenarioParameters (System.Fabric.PartitionSelector partitionSelector, TimeSpan timeToRun, TimeSpan maxServiceStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan timeToRun, valuetype System.TimeSpan maxServiceStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.#ctor(System.Fabric.PartitionSelector,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.FailoverTestScenarioParameters : System.Fabric.PartitionSelector * TimeSpan * TimeSpan -&gt; System.Fabric.Testability.Scenario.FailoverTestScenarioParameters" Usage="new System.Fabric.Testability.Scenario.FailoverTestScenarioParameters (partitionSelector, timeToRun, maxServiceStabilizationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="maxServiceStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">PartitionSelector, wodurch die Partition, das das Ziel für den Test zu erhalten.</param>
        <param name="timeToRun">Die Gesamtzeit für die der Failover-Test ausgeführt wird.</param>
        <param name="maxServiceStabilizationTimeout">Die maximale Zeitdauer, die für den Dienst nach einem Fehler, bevor der Test fehlschlägt stabilisiert gewartet.</param>
        <summary>
            Der Konstruktor für die FailoverTestScenarioParameters.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxServiceStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxServiceStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxServiceStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.MaxServiceStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxServiceStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxServiceStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.MaxServiceStabilizationTimeout" />
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
            Die maximale Zeitdauer, die für den Dienst nach einem Fehler, bevor der Test fehlschlägt stabilisiert gewartet.
            </summary>
        <value>
            Vor dem Start Ausübung der Failover-Szenarien wartet FailoverTestScenario höchstens dieser Zeitspanne für den Dienst stabilisiert und fehlerfrei sind.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionSelector">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionSelector PartitionSelector { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.PartitionSelector PartitionSelector" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.PartitionSelector" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionSelector As PartitionSelector" />
      <MemberSignature Language="F#" Value="member this.PartitionSelector : System.Fabric.PartitionSelector with get, set" Usage="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.PartitionSelector" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die PartitionSelector die Partition enthält, die für den Test bereitgestellt werden muss.
            </summary>
        <value>
            Gibt <see cref="T:System.Fabric.PartitionSelector" /> zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>