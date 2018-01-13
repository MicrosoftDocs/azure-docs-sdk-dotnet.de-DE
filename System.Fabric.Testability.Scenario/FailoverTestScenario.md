<Type Name="FailoverTestScenario" FullName="System.Fabric.Testability.Scenario.FailoverTestScenario">
  <TypeSignature Language="C#" Value="public sealed class FailoverTestScenario : System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FailoverTestScenario extends System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.FailoverTestScenario" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FailoverTestScenario&#xA;Inherits TestScenario" />
  <TypeSignature Language="F#" Value="type FailoverTestScenario = class&#xA;    inherit TestScenario" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenario</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die FailoverTestScenario ist ein Test, der eine Reihe von Fehlern für eine bestimmte Partition, die durch die PartitionSelector in der FailoverTestScenarioParameters definierten ausgeführt wird.
            </summary>
    <remarks>
            Tritt ein Fehler im induziert versetzen die Partition über einige bestimmte Failover-Szenarien, um sicherzustellen, dass diese Pfade getestet und untersucht werden. Die Arbeitslast für den Dienst zur gleichen Zeit wie der Test ausgeführt wird, erhöhen Sie die Chancen einer ratenbasierte und Erkennen von Fehlern mit dem Dienst. Der Fehler ausgelöst wird, für das primäre, sekundäre Datenbanken und Instanzen ohne Status sind RestartReplica(only persisted), RemoveReplica, ResartDeployedCodePackage, MovePrimary (nur zustandsbehaftet), (nur zustandsbehaftete) MoveSecondary RestartPartition (ohne Datenverlust).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverTestScenario (System.Fabric.FabricClient fabricClient, System.Fabric.Testability.Scenario.FailoverTestScenarioParameters testScenarioParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClient fabricClient, class System.Fabric.Testability.Scenario.FailoverTestScenarioParameters testScenarioParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.#ctor(System.Fabric.FabricClient,System.Fabric.Testability.Scenario.FailoverTestScenarioParameters)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.FailoverTestScenario : System.Fabric.FabricClient * System.Fabric.Testability.Scenario.FailoverTestScenarioParameters -&gt; System.Fabric.Testability.Scenario.FailoverTestScenario" Usage="new System.Fabric.Testability.Scenario.FailoverTestScenario (fabricClient, testScenarioParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricClient" Type="System.Fabric.FabricClient" />
        <Parameter Name="testScenarioParameters" Type="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters" />
      </Parameters>
      <Docs>
        <param name="fabricClient">FabricClient-Objekt, die zum Herstellen einer Verbindung mit dem Cluster und die Fehler auslösen verwendet werden soll.</param>
        <param name="testScenarioParameters">FailoverTestScenarioParameters die definieren, die Konfiguration für das Failover testen.</param>
        <summary>
            Der Konstruktor für die FailoverTestScenario.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected override void OnDispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.OnDispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnDispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnDispose : bool -&gt; unit" Usage="failoverTestScenario.OnDispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</param>
        <summary>
            Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnExecuteAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnExecuteAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnExecuteAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.OnExecuteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnExecuteAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.OnExecuteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="failoverTestScenario.OnExecuteAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.FailoverTestScenario/&lt;OnExecuteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</param>
        <summary>
            Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateScenarioAtExitAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task ValidateScenarioAtExitAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task ValidateScenarioAtExitAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.ValidateScenarioAtExitAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateScenarioAtExitAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.ValidateScenarioAtExitAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="failoverTestScenario.ValidateScenarioAtExitAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.FailoverTestScenario/&lt;ValidateScenarioAtExitAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</param>
        <summary>
            Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>