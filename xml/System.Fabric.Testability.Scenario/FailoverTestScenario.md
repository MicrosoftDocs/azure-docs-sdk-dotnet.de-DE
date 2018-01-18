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
            <span data-ttu-id="8eea4-101">Die FailoverTestScenario ist ein Test, der eine Reihe von Fehlern für eine bestimmte Partition, die durch die PartitionSelector in der FailoverTestScenarioParameters definierten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="8eea4-101">The FailoverTestScenario is a test which runs a series of faults against a specific partition defined by the PartitionSelector in the FailoverTestScenarioParameters.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8eea4-102">Tritt ein Fehler im induziert versetzen die Partition über einige bestimmte Failover-Szenarien, um sicherzustellen, dass diese Pfade getestet und untersucht werden.</span><span class="sxs-lookup"><span data-stu-id="8eea4-102">The faults induced put the partition through some specific failover scenarios to ensure those paths are tested and exercised.</span></span> <span data-ttu-id="8eea4-103">Die Arbeitslast für den Dienst zur gleichen Zeit wie der Test ausgeführt wird, erhöhen Sie die Chancen einer ratenbasierte und Erkennen von Fehlern mit dem Dienst.</span><span class="sxs-lookup"><span data-stu-id="8eea4-103">Running your workload against the service at the same time as the test being run will increase the chances of inducing and discovering bugs with the service.</span></span> <span data-ttu-id="8eea4-104">Der Fehler ausgelöst wird, für das primäre, sekundäre Datenbanken und Instanzen ohne Status sind RestartReplica(only persisted), RemoveReplica, ResartDeployedCodePackage, MovePrimary (nur zustandsbehaftet), (nur zustandsbehaftete) MoveSecondary RestartPartition (ohne Datenverlust).</span><span class="sxs-lookup"><span data-stu-id="8eea4-104">The faults induced for the Primary, Secondaries and stateless instances are RestartReplica(only persisted), RemoveReplica, ResartDeployedCodePackage, MovePrimary (only stateful), MoveSecondary (Only stateful), RestartPartition (no data loss).</span></span>
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
        <param name="fabricClient"><span data-ttu-id="8eea4-105">FabricClient-Objekt, die zum Herstellen einer Verbindung mit dem Cluster und die Fehler auslösen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8eea4-105">FabricClient object which will be used to connect to the cluster and induce the faults.</span></span></param>
        <param name="testScenarioParameters"><span data-ttu-id="8eea4-106">FailoverTestScenarioParameters die definieren, die Konfiguration für das Failover testen.</span><span class="sxs-lookup"><span data-stu-id="8eea4-106">FailoverTestScenarioParameters which define the configuration for the failover test.</span></span></param>
        <summary>
            <span data-ttu-id="8eea4-107">Der Konstruktor für die FailoverTestScenario.</span><span class="sxs-lookup"><span data-stu-id="8eea4-107">Constructor for the FailoverTestScenario.</span></span>
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
        <param name="disposing"><span data-ttu-id="8eea4-108">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8eea4-108">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="8eea4-109">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8eea4-109">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
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
        <param name="token"><span data-ttu-id="8eea4-110">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8eea4-110">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="8eea4-111">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8eea4-111">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
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
        <param name="token"><span data-ttu-id="8eea4-112">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8eea4-112">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="8eea4-113">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="8eea4-113">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>