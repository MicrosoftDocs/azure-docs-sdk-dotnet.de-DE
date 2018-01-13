<Type Name="FabricClient+TestManagementClient" FullName="System.Fabric.FabricClient+TestManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.TestManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/TestManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.TestManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.TestManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.TestManagementClient = class" />
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
      <para>Stellt Methoden zum Ausstellen und Test-Befehle zu steuern.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="operationId">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</param>
        <param name="force">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.  Siehe Hinweise.</param>
        <summary>
            Bricht einen Testbefehl ab.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.  Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.  Angeben von Force als "true" sollte mit Vorsicht verwendet werden.  Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.
            Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.  Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.  Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.  
            Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.
            
            
            </para>
          <para>
            Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.  CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</param>
        <param name="force">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.  Siehe Hinweise.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Bricht einen Testbefehl ab.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.  Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.  Angeben von Force als "true" sollte mit Vorsicht verwendet werden.  Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.
            Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.  Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.  Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.  
            Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.
            
            
            
            </para>
          <para>
            Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.  CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</param>
        <param name="force">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.  Siehe Hinweise.</param>
        <param name="timeout">Das Timeout für den API-Aufruf verwendet werden soll.</param>
        <summary>
            Bricht einen Testbefehl ab.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.  Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.  Angeben von Force als "true" sollte mit Vorsicht verwendet werden.  Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.
            Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.  Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.  Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.  
            Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.
            
            
            
            </para>
          <para>
            Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.  CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</param>
        <param name="force">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.  Siehe Hinweise.</param>
        <param name="timeout">Das Timeout für den API-Aufruf verwendet werden soll.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Bricht einen Testbefehl ab.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.  Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.  Angeben von Force als "true" sollte mit Vorsicht verwendet werden.  Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.
            Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.  Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.  Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.  
            Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.
            
            
            
            </para>
          <para>
            Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.  CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Bereinigt alle Teststatus im Cluster.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>
            Bereinigt alle Testzustand in den Cluster, der für die Fehlertoleranz Vorgänge festgelegt wurde; wie stopnode-Aufruf steht sollten InvokeDataLoss, RestartPartition und InvokeQuorumLoss diese API aufgerufen, wenn nicht mehr aktiv ist oder wenn der Testtreiber nicht verarbeiten oder ein Vorgang abgebrochen wird, während in-Flight aus, um sicherzustellen, dass der Cluster wieder in den Zustand "normal" ist einer dieser Vorgänge ein Fehler auf. Normalerweise alle Fehler Vorgänge Bereinigen von ihren Status am Ende der Ausführung der API so CleanTestState muss nur aufgerufen werden, wenn die API-Vorgang unterbrochen wird.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync (TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync (operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync (operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Bereinigt alle Teststatus im Cluster.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>
            Bereinigt alle der Testzustand in den Cluster, der für Vorgänge der Fehlertoleranz, InvokeDataLoss, RestartPartition und InvokeQuorumLoss diese API festgelegt wurde aufgerufen werden, falls diese Vorgänge nicht oder wenn der Test-Treiber Prozess Dies oder einen Vorgang abgebrochen wird zwar Flight, um sicherzustellen, dass der Cluster wieder in den Zustand "normal" befindet. Normalerweise alle Fehler Vorgänge Bereinigen von ihren Status am Ende der Ausführung der API so CleanTestState muss nur aufgerufen werden, wenn die API-Vorgang unterbrochen wird.
            </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (filter As ChaosReportFilter) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
      </Parameters>
      <Docs>
        <param name="filter">Filter für die <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s, im Bericht eingeschlossen werden sollen.</param>
        <summary>
            Ruft ab den Bericht über Chaos ausgeführt wird.
            </summary>
        <returns>Bericht der Chaos ausgeführt wird.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.Fabric.FabricException">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.
            FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (continuationToken As String) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync continuationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="continuationToken">Fortsetzungstoken für die Liste der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</param>
        <summary>
            Ruft ab den Bericht über Chaos ausgeführt wird.
            </summary>
        <returns>Bericht der Chaos ausgeführt wird.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.
            FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (filter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filter">Filter für die <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s im einzuschließenden der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <param name="cancellationToken">Abbruchtoken.</param>
        <summary>
            Ruft ab den Bericht über Chaos ausgeführt wird.
            </summary>
        <returns>Bericht der Chaos ausgeführt wird.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricException">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.
            FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (continuationToken, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">Fortsetzungstoken für die Liste der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <param name="cancellationToken">Abbruchtoken.</param>
        <summary>
            Ruft ab den Bericht über Chaos ausgeführt wird.
            </summary>
        <returns>Bericht der Chaos ausgeführt wird.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.
            FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeTransitionProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetNodeTransitionProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeTransitionProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;" Usage="testManagementClient.GetNodeTransitionProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn der Testbefehl mit StartNodeTransitionAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Befehls mit StartNodeTransitionAsync() gestartet.
            </summary>
        <returns>Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionDataLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionDataLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionDataLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionDataLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>
            Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionQuorumLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
                - FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>
            Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionQuorumLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
                - FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>
            Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionQuorumLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
                - FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.
            </summary>
        <returns>Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>
            Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionQuorumLossProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
                - FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.
                - FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.
            </summary>
        <returns>Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionRestartProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.
            </summary>
        <returns>Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionRestartProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.
            </summary>
        <returns>Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionRestartProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</param>
        <param name="timeout">Timeout</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.
            </summary>
        <returns>Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</returns>
        <remarks>
          <para>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</para>
          <para>Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.
            PartitionRestartProgress.Result.Exception Werte:
              - ArgumentException - Eingabe ist ungültig.
              - FabricException mit einer ErrorCode-Eigenschaft der:
                - PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status des Test-Befehle.
            </summary>
        <returns>Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTestCommandStatusListAsync (operationTimeout As TimeSpan) As Task(Of TestCommandStatusList)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">Ein Timeout für die API-Aufruf.</param>
        <summary>
            Ruft den Status des Test-Befehle.
            </summary>
        <returns>Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">Ein Timeout für die API-Aufruf.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status des Test-Befehle.
            </summary>
        <returns>Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter">Dieser Parameter kann verwendet werden, um nach TestCommandState zu filtern</param>
        <param name="operationTimeout">Ein Timeout für die API-Aufruf.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status des Test-Befehle.
            </summary>
        <returns>Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="typeFilter">Dieser Parameter kann verwendet werden, um nach TestCommandType zu filtern</param>
        <param name="operationTimeout">Ein Timeout für die API-Aufruf.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status des Test-Befehle.
            </summary>
        <returns>Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter">Dieser Parameter kann verwendet werden, um nach TestCommandState zu filtern</param>
        <param name="typeFilter">Dieser Parameter kann verwendet werden, um nach TestCommandType zu filtern</param>
        <param name="operationTimeout">Ein Timeout für die API-Aufruf.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft den Status des Test-Befehle.
            </summary>
        <returns>Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumLossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.                 
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumLossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <param name="cancellationToken">Das Abbruchtoken, das für den Vorgang.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumLossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <param name="operationTimeout">Allgemeines Timeout für den gesamten Vorgang.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumlossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <param name="operationTimeout">Allgemeines Timeout für den gesamten Vorgang.</param>
        <param name="cancellationToken">Das Abbruchtoken, das für den Vorgang.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die angibt, dass der Partitions, die muss neu gestartet werden</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.  Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.  
            Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync chaosParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
      </Parameters>
      <Docs>
        <param name="chaosParameters">
          <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />enthält verschiedene Parameter zum Steuern von Chaos; z. B. Zeit ausgeführt wird, maximale Anzahl von gleichzeitigen Fautls usw. </param>
        <summary>
            Diese API wird mit den angegebenen Parameterwerten Chaos gestartet.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException">Diese Ausnahme wird ausgelöst, wenn die StartChaos-API aufgerufen wird, während Chaos bereits im Cluster ausgeführt wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync (chaosParameters, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="chaosParameters"> Enthält verschiedene Parameter zum Steuern von Chaos; z. B. Zeit ausgeführt wird, maximale Anzahl von gleichzeitigen Fehlern usw.</param>
        <param name="operationTimeout"> Das gesamttimeout für den Vorgang.</param>
        <param name="cancellationToken"> Abbruchtoken.</param>
        <summary>
            Diese API wird mit den angegebenen Parameterwerten Chaos gestartet.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException">Diese Ausnahme wird ausgelöst, wenn die StartChaos-API aufgerufen wird, während Chaos bereits im Cluster ausgeführt wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeTransitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartNodeTransitionAsync (System.Fabric.Description.NodeTransitionDescription description, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartNodeTransitionAsync(class System.Fabric.Description.NodeTransitionDescription description, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartNodeTransitionAsync(System.Fabric.Description.NodeTransitionDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function StartNodeTransitionAsync (description As NodeTransitionDescription, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.StartNodeTransitionAsync : System.Fabric.Description.NodeTransitionDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartNodeTransitionAsync (description, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.NodeTransitionDescription" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">Ein Objekt der Art des Knotens Übergangs auszuführenden beschrieben wird.  Der Übergang kann zum Starten oder Beenden eines Knotens sein.</param>
        <param name="operationTimeout">Das Timeout für diesen API-Aufruf.</param>
        <param name="token">Das cancellationToken</param>
        <summary>
            Startet oder beendet einen Clusterknoten.  Ein Clusterknoten ist ein Prozess, nicht die Betriebssysteminstanz selbst.  Um einen Knoten zu starten, übergeben Sie ein Objekt des Typs NodeStartDescription in der Description-Parameter.  Um einen Knoten zu beenden, übergeben Sie ein Objekt vom Typ NodeStopDescription.  Nachdem diese API zurückgegeben hat, rufen Sie GetNodeTransitionProgressAsync(), um den Fortschritt des Vorgangs abzurufen.
            </summary>
        <returns>Eine Aufgabe</returns>
        <remarks>Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</remarks>
        <exception cref="T:System.Fabric.FabricException">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.        
              Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.      
            </exception>
        <exception cref="T:System.TimeoutException">Beim Vorgang ist ein Timeout aufgetreten.</exception>
        <exception cref="T:System.ArgumentNullException">Ein Argument mit einem Wert von Null übergeben wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust verursacht werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" />.
            PartialDataLoss - nur ein Quorum der Replikate werden entfernt und OnDataLoss wird ausgelöst, für die Partition tatsächlich Datenverlust hängt jedoch Vorhandensein von in-Flight-Replikation.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden. CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.
            Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Hierbei handelt es sich um die Fabric-Fehler.
            FabricErrorCode.PartitionNotFound - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
          <para>
            Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.  CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.  
            Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
          <para>
            Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.  CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.  
            Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</param>
        <param name="dataLossMode">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API wird Datenverlust für die angegebene Partition auslösen. Löst einen Aufruf der API OnDataLoss der Partition.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.
            Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
          <para>
            Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.  CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.
            Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> Ein vom Benutzer bereitgestellte-Bezeichner.  Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</param>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumLossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> Ein vom Benutzer bereitgestellte-Bezeichner.  Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</param>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumLossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <param name="cancellationToken">Das Abbruchtoken, das für den Vorgang.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> Ein vom Benutzer bereitgestellte-Bezeichner.  Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</param>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumLossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <param name="operationTimeout">Allgemeines Timeout für den gesamten Vorgang.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> Ein vom Benutzer bereitgestellte-Bezeichner.  Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</param>
        <param name="partitionSelector">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht. <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode">PartialQuorumLoss oder FullQuorumLoss.</param>
        <param name="quorumlossDuration">Zeitdauer für die Partition in quorumsverlust bleiben.</param>
        <param name="operationTimeout">Allgemeines Timeout für den gesamten Vorgang.</param>
        <param name="cancellationToken">Das Abbruchtoken, das für den Vorgang.</param>
        <summary>Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus. </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.
            PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...
            </para>
          <para>
            QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen. Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.
            </para>
          <para>
            Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.
            </para>
          <para>
            Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.OperationCanceledException">Asynchroner Vorgang abgebrochen wird.</exception>
        <exception cref="T:System.InvalidOperationException"> Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.  
            Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.  Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.  Finden Sie unter GetPartitionRestartProgressAsync().
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.ArgumentException">Die Eingabe ist ungültig.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die angibt, dass der Partitions, die muss neu gestartet werden</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.  
            Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.  Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.  Finden Sie unter GetPartitionRestartProgressAsync().
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.ArgumentException">Die Eingabe ist ungültig.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.  
            Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.  Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.  Finden Sie unter GetPartitionRestartProgressAsync().
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.ArgumentException">Die Eingabe ist ungültig.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</param>
        <param name="restartPartitionMode">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</param>
        <param name="operationTimeout">Das gesamttimeout für den Vorgang.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.
            </para>
          <para>
            Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.  
            Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.  Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.  Finden Sie unter GetPartitionRestartProgressAsync().
            </para>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.             
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.ArgumentException">Die Eingabe ist ungültig.</exception>
        <exception cref="T:System.Fabric.FabricException">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</exception>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function StopChaosAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Diese API wird Chaos beendet.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"> Das gesamttimeout für den Vorgang.</param>
        <param name="cancellationToken"> Abbruchtoken</param>
        <summary>
            Diese API wird Chaos beendet.
            </summary>
        <returns>Eine Aufgabe.</returns>
        <remarks>
          <para>
            Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der Name der Anwendung, deren Dienste überprüft werden müssen.</param>
        <param name="maximumStabilizationTimeout">Max. Zeitraum, für die Dienste anderer Fehler stabilisiert warten Sie den Vorgang.</param>
        <summary>
            Diese API wird die Verfügbarkeit und Integrität aller Dienste in der angegebenen Anwendung überprüfen.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricValidationException">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der Name der Anwendung, deren Dienste überprüft werden müssen.</param>
        <param name="maximumStabilizationTimeout">Max. Zeitraum, für die Dienste anderer Fehler stabilisiert warten Sie den Vorgang.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird die Verfügbarkeit und Integrität aller Dienste in der angegebenen Anwendung überprüfen.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricValidationException">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">Der Name der Anwendung, deren Dienste überprüft werden müssen.</param>
        <param name="maximumStabilizationTimeout">Max. Zeitraum, für die Dienste anderer Fehler stabilisiert warten Sie den Vorgang.</param>
        <param name="operationTimeout">Die Zeitspanne auf den Vorgang andernfalls Fail Abschluss eines Vorgangs zu warten.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird die Verfügbarkeit und Integrität aller Dienste in der angegebenen Anwendung überprüfen.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricValidationException">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, der überprüft werden muss.</param>
        <param name="maximumStabilizationTimeout">Max. Zeitraum, für den Dienst else Fail stabilisiert warten Sie den Vorgang.</param>
        <summary>
            Diese API wird die Verfügbarkeit und Integrität des angegebenen Diensts überprüfen.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricValidationException">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, der überprüft werden muss.</param>
        <param name="maximumStabilizationTimeout">Max. Zeitraum, für den Dienst else Fail stabilisiert warten Sie den Vorgang.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird die Verfügbarkeit und Integrität des angegebenen Diensts überprüfen.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricValidationException">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">Der Name des Diensts, der überprüft werden muss.</param>
        <param name="maximumStabilizationTimeout">Max. Zeitraum, für den Dienst else Fail stabilisiert warten Sie den Vorgang.</param>
        <param name="operationTimeout">Die Zeitspanne auf den Vorgang andernfalls Fail Abschluss eines Vorgangs zu warten.</param>
        <param name="token">Abbruchtoken</param>
        <summary>
            Diese API wird die Verfügbarkeit und Integrität des angegebenen Diensts überprüfen.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Aktion dauerte länger als der vorgesehenen Zeit.</exception>
        <exception cref="T:System.ArgumentNullException">Eines der erforderlichen Argumente sind null.</exception>
        <exception cref="T:System.Fabric.FabricValidationException">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</exception>
      </Docs>
    </Member>
  </Members>
</Type>