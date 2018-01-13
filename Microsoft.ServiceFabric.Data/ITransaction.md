<Type Name="ITransaction" FullName="Microsoft.ServiceFabric.Data.ITransaction">
  <TypeSignature Language="C#" Value="public interface ITransaction : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransaction implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ITransaction" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransaction&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ITransaction = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             Eine Sequenz von Vorgängen werden als einzelne logische Arbeitseinheit ausgeführt.
             </summary>
    <remarks>
             Eine Transaktion muss die folgenden ACID-Eigenschaften aufweisen. (finden Sie unter: https://technet.microsoft.com/en-us/library/ms190612) <list type="bullet"> <item> <description> Unteilbarkeit - in eine Transaktion muss eine unteilbare Arbeitseinheit; entweder werden alle vorgesehenen datenänderungen ausgeführt oder keine von ihnen ausgeführt wird. </description></item><item><description>Konsistenz - muss nach Abschluss eine Transaktion alle Daten in einem konsistenten Zustand lassen. Alle internen Datenstrukturen müssen am Ende der Transaktion korrekt sein. </description></item><item><description>Isolation - Änderungen, die von gleichzeitigen Transaktionen müssen von den Änderungen, die von anderen gleichzeitigen Transaktionen isoliert sein. Die Isolationsstufe für einen Vorgang in einem <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> richtet sich nach der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Ausführen des Vorgangs. </description></item><item><description>Dauerhaftigkeit - nach dem Abschluss einer Transaktions sind ihre Auswirkungen dauerhaft im System. Die Änderungen bleiben sogar auch bei Systemausfällen erhalten. </description></item></list><para>Beliebiger Instanzmember dieses Typs wird nicht unbedingt threadsicher sein. Dies macht Transaktionen auf die Einheit der Parallelität: Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden einzeln an. Alle <see cref="T:IReliableCollection{T}" /> APIs, annehmen, eine Transaktion und der Rückgabewert eine Aufgabe muss, erwartet einzeln nacheinander. </para><para>Es folgt ein Beispiel für eine richtige Verwendung.
             <code><![CDATA[
                         
                         while (true)
                     {
                         cancellationToken.ThrowIfCancellationRequested();
                         
                     try
                         {
                         using (var tx = this.StateManager.CreateTransaction())
                         {
                         await concurrentQueue.EnqueueAsync(tx, 12L, cancellationToken);
                     await tx.CommitAsync();
                         
                         return;
                     }
             }
             catch (TransactionFaultedException e)
             {
             // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
             // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
             Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
             }
                 catch (FabricNotPrimaryException e)
                 {
                     // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
             // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                     Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                     return;
                         }
                         catch (FabricNotReadableException e)
                             {
                             // Retry until the queue is readable or a different exception is thrown.
            Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
                             }
                         catch (FabricObjectClosedException e)
                     {
                     // Gracefully exit RunAsync as this is happening due to replica close.
                     // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                         Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                         return;
                         }
                     catch (TimeoutException e)
                     {
                     Console.WriteLine("Encountered TimeoutException during EnqueueAsync, retrying the transaction: " + e);
                         }
                         
                         // Delay and retry.
                         await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                     }
                     ]]></code></para><para>Im folgenden ist ein Beispiel für falsche Verwendung, die Verhalten nicht definiert wurde.
                     <code><![CDATA[
                         using (var txn = this.StateManager.CreateTransaction())
                         {
                     List<Task> taskList = new List<Task>();
                     taskList.Add(concurrentQueue.DequeueAsync(txn, cancellationToken));
                     taskList.Add(concurrentQueue.DequeueAsync(txn, cancellationToken));
                         
                         await Task.WhenAll(taskList);
                         await txn.CommitAsync();
                         }
                     ]]></code></para></remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iTransaction.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Abbruch Rollback () der Transaktion.
            </summary>
        <remarks>
          <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
          <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
          <exception cref="T:System.Fabric.FabricNotPrimaryException">
            Die Transaktion umfasst Updates für <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> und <see cref="T:System.Fabric.ReplicaRole" /> hat nicht die primäre.
            Nur primäre Replikate Schreibstatus erhalten.
            </exception>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CommitAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.CommitAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CommitAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CommitAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iTransaction.CommitAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Commit für die Transaktion aus.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Commitvorgang darstellt. 
            </returns>
        <remarks>
            Eine Transaktion kann nicht abgebrochen werden, nachdem sie ein Commit ausgeführt wurde, da alle Änderungen persistent gespeichert und repliziert wurden.
            </remarks>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
            Die Transaktion umfasst Updates für <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> und <see cref="T:System.Fabric.ReplicaRole" /> hat nicht die primäre.
            Nur primäre Replikate Schreibstatus erhalten.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CommitSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommitSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommitSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ITransaction.CommitSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommitSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommitSequenceNumber : int64" Usage="Microsoft.ServiceFabric.Data.ITransaction.CommitSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Sequenznummer für den Commitvorgang.
            </summary>
        <value>
            Die Sequenznummer, an dem die Transaktion ein Commit ausgeführt wurde.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVisibilitySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetVisibilitySequenceNumberAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetVisibilitySequenceNumberAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.GetVisibilitySequenceNumberAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVisibilitySequenceNumberAsync () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member GetVisibilitySequenceNumberAsync : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iTransaction.GetVisibilitySequenceNumberAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Sichtbarkeit Sequenznummer ab.
            </summary>
        <returns>Die Sequenznummer der Sichtbarkeit.</returns>
        <remarks>
          <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
          <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionId">
      <MemberSignature Language="C#" Value="public long TransactionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransactionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ITransaction.TransactionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransactionId As Long" />
      <MemberSignature Language="F#" Value="member this.TransactionId : int64" Usage="Microsoft.ServiceFabric.Data.ITransaction.TransactionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der die Transaktion identifiziert.
            </summary>
        <value>Die Transaktions-Id.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>