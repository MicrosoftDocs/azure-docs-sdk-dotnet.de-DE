<Type Name="ChaosTestScenario" FullName="System.Fabric.Testability.Scenario.ChaosTestScenario">
  <TypeSignature Language="C#" Value="public sealed class ChaosTestScenario : System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ChaosTestScenario extends System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.ChaosTestScenario" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ChaosTestScenario&#xA;Inherits TestScenario" />
  <TypeSignature Language="F#" Value="type ChaosTestScenario = class&#xA;    inherit TestScenario" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenario</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This class is deprecated. To manage Chaos, please use StartChaosAsync, StopChaosAsync, and GetChaosReportAsync APIs from FabricClient.TestManager instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0811c-101">Die ChaosTestScenario ist ein langer Szenario die ratenbasierte behält Failover und Fehlern in den Cluster, bis die TimetoRun abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="0811c-101">The ChaosTestScenario is a long running scenario which keeps inducing failover and faults into the cluster up until the TimetoRun has expired.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="0811c-102">Der Test wird jeder Iteration bis zu "MaxConcurrentFaults" Auslösen und anschließend überprüft die Integrität und Verfügbarkeit aller Dienste im Cluster vor dem Wechsel auf in der nächsten Iteration der Fehler.</span><span class="sxs-lookup"><span data-stu-id="0811c-102">The test will induce up to 'maxConcurrentFaults' every iteration and then will validate the health and availability of all the services in the cluster before moving on to the next iteration of faults.</span></span> <span data-ttu-id="0811c-103">Wenn an einem beliebigen Punkt der Dienste nicht verfügbar sind oder fehlerfrei durch "MaxClusterStabilizationTimeout" der Test schlägt mit einer FabricValidationException fehl.</span><span class="sxs-lookup"><span data-stu-id="0811c-103">If at any point the services are not available or healthy by 'maxClusterStabilizationTimeout' the test will fail with a FabricValidationException.</span></span> <span data-ttu-id="0811c-104">Für jede Iteration Sicherstellen der gleichzeitigen Fehlern, die in das System verursacht werden Sicherheit so, dass der Fehler zusammen nicht verursacht jeder Dienst nicht mehr verfügbar oder Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="0811c-104">For every iteration the concurrent faults that are induced into the system ensure safety such that the faults together will not cause any service to become unavailable or lose any data.</span></span> <span data-ttu-id="0811c-105">Dabei wird vorausgesetzt, kein Fehler ausgelöst wird, aus der Außenseite oder alle unerwarteten Ausfällen, die was, wenn sie (mit dem Test-Fehlern Chaos gleichzeitige) waren Verfügbarkeit Datenverlust führen kann.</span><span class="sxs-lookup"><span data-stu-id="0811c-105">This assumes no faults induced from the outside or any unexpected failures which if they happen (concurrent with the chaos test faults) can cause data availability loss.</span></span> <span data-ttu-id="0811c-106">Dies ist ein sehr gutes Test für den Test auszuführen, oder Arbeitslasten testen die staging-Cluster ausgeführt werden, um sicherzustellen, dass Fehler im System keine Art von Verfügbarkeit Verlust oder anderen unerwarteten Problemen führen.</span><span class="sxs-lookup"><span data-stu-id="0811c-106">This is a very good test to run against your test or staging clusters which test workloads are running to ensure that faults in the system do not result in any sort of availability loss or other unexpected service issues.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosTestScenario (System.Fabric.FabricClient fabricClient, System.Fabric.Testability.Scenario.ChaosTestScenarioParameters chaosScenarioParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClient fabricClient, class System.Fabric.Testability.Scenario.ChaosTestScenarioParameters chaosScenarioParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.#ctor(System.Fabric.FabricClient,System.Fabric.Testability.Scenario.ChaosTestScenarioParameters)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.ChaosTestScenario : System.Fabric.FabricClient * System.Fabric.Testability.Scenario.ChaosTestScenarioParameters -&gt; System.Fabric.Testability.Scenario.ChaosTestScenario" Usage="new System.Fabric.Testability.Scenario.ChaosTestScenario (fabricClient, chaosScenarioParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricClient" Type="System.Fabric.FabricClient" />
        <Parameter Name="chaosScenarioParameters" Type="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" />
      </Parameters>
      <Docs>
        <param name="fabricClient"><span data-ttu-id="0811c-107">FabricClient-Objekt, die zum Herstellen einer Verbindung mit dem Cluster und die Fehler auslösen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0811c-107">FabricClient object which will be used to connect to the cluster and induce the faults.</span></span></param>
        <param name="chaosScenarioParameters"><span data-ttu-id="0811c-108">ChaosTestScenarioParameters, die die Konfiguration für den Test Chaos zu definieren.</span><span class="sxs-lookup"><span data-stu-id="0811c-108">ChaosTestScenarioParameters which define the configuration for the chaos test.</span></span></param>
        <summary>
            <span data-ttu-id="0811c-109">Der Konstruktor für die ChaosTestScenario.</span><span class="sxs-lookup"><span data-stu-id="0811c-109">Constructor for the ChaosTestScenario.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected override void OnDispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.OnDispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnDispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnDispose : bool -&gt; unit" Usage="chaosTestScenario.OnDispose disposing" />
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
        <param name="disposing"><span data-ttu-id="0811c-110">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="0811c-110">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="0811c-111">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="0811c-111">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnExecuteAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnExecuteAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnExecuteAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.OnExecuteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnExecuteAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.OnExecuteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="chaosTestScenario.OnExecuteAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.ChaosTestScenario/&lt;OnExecuteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0811c-112">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="0811c-112">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="0811c-113">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="0811c-113">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateScenarioAtExitAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task ValidateScenarioAtExitAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task ValidateScenarioAtExitAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.ValidateScenarioAtExitAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateScenarioAtExitAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.ValidateScenarioAtExitAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="chaosTestScenario.ValidateScenarioAtExitAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.ChaosTestScenario/&lt;ValidateScenarioAtExitAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="0811c-114">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="0811c-114">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="0811c-115">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="0811c-115">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>