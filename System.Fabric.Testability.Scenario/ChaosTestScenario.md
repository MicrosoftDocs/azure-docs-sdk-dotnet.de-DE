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
            Die ChaosTestScenario ist ein langer Szenario die ratenbasierte behält Failover und Fehlern in den Cluster, bis die TimetoRun abgelaufen ist.
            </summary>
    <remarks>
            Der Test wird jeder Iteration bis zu "MaxConcurrentFaults" Auslösen und anschließend überprüft die Integrität und Verfügbarkeit aller Dienste im Cluster vor dem Wechsel auf in der nächsten Iteration der Fehler. Wenn an einem beliebigen Punkt der Dienste nicht verfügbar sind oder fehlerfrei durch "MaxClusterStabilizationTimeout" der Test schlägt mit einer FabricValidationException fehl. Für jede Iteration Sicherstellen der gleichzeitigen Fehlern, die in das System verursacht werden Sicherheit so, dass der Fehler zusammen nicht verursacht jeder Dienst nicht mehr verfügbar oder Daten verloren gehen. Dabei wird vorausgesetzt, kein Fehler ausgelöst wird, aus der Außenseite oder alle unerwarteten Ausfällen, die was, wenn sie (mit dem Test-Fehlern Chaos gleichzeitige) waren Verfügbarkeit Datenverlust führen kann. Dies ist ein sehr gutes Test für den Test auszuführen, oder Arbeitslasten testen die staging-Cluster ausgeführt werden, um sicherzustellen, dass Fehler im System keine Art von Verfügbarkeit Verlust oder anderen unerwarteten Problemen führen.
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
        <param name="fabricClient">FabricClient-Objekt, die zum Herstellen einer Verbindung mit dem Cluster und die Fehler auslösen verwendet werden soll.</param>
        <param name="chaosScenarioParameters">ChaosTestScenarioParameters, die die Konfiguration für den Test Chaos zu definieren.</param>
        <summary>
            Der Konstruktor für die ChaosTestScenario.
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