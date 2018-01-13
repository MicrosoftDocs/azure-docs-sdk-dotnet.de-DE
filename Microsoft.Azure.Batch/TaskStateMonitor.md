<Type Name="TaskStateMonitor" FullName="Microsoft.Azure.Batch.TaskStateMonitor">
  <TypeSignature Language="C#" Value="public class TaskStateMonitor : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskStateMonitor extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskStateMonitor" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskStateMonitor&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type TaskStateMonitor = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Bietet Hilfsprogramme, die überwacht werden können CloudTask Status an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.TaskStateMonitor" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</para>
          <para>Änderungen werden in der Reihenfolge der Auflistung angewendet. Der letzte write Wins.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitAll">
      <MemberSignature Language="C#" Value="public void WaitAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, TimeSpan timeout, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void WaitAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.TimeSpan timeout, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WaitAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub WaitAll (tasksToMonitor As IEnumerable(Of CloudTask), desiredState As TaskState, timeout As TimeSpan, Optional controlParams As ODATAMonitorControl = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.WaitAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * TimeSpan * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="taskStateMonitor.WaitAll (tasksToMonitor, desiredState, timeout, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor">Die Auflistung von Aufgaben zu überwachen.</param>
        <param name="desiredState">Die vorhergesagten Status der Aufgaben. Die Methode wird beendet, wenn alle Aufgaben mindestens einmal dieser Status erreicht haben.</param>
        <param name="timeout">Die maximale Zeitspanne an, diesen Aufruf, bevor ein Timeout auftritt wartet.</param>
        <param name="controlParams">Steuert verschiedene Einstellungen des Monitors, z. B. Verzögerung zwischen den einzelnen an.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</param>
        <summary>
            Monitore eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Auflistung erst jedes seiner Member mindestens einmal einen gewünschten Zustand erreicht.
            </summary>
        <remarks>
          <para>
            Der Status der einzelnen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanz wird davon ausgegangen, dass autorisierende zum Zeitpunkt des Aufrufs.
            Instanzen, die bereits an die <paramref name="desiredState" /> werden ignoriert.
            Die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen in der Auflistung als schreibgeschützt behandelt werden.
            Dies bedeutet, dass bei Beendigung des Aufrufs (Timeout oder nicht) die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen sollte vor der Verwendung aktualisiert werden.
            </para>
          <para>
            Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn die <paramref name="timeout" /> ist abgelaufen.</exception>
      </Docs>
    </Member>
    <Member MemberName="WhenAll">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WhenAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, System.Threading.CancellationToken cancellationToken, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task WhenAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.Threading.CancellationToken,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.WhenAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * System.Threading.CancellationToken * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="taskStateMonitor.WhenAll (tasksToMonitor, desiredState, cancellationToken, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.TaskStateMonitor/&lt;WhenAll&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor">Die Auflistung von Aufgaben zu überwachen.</param>
        <param name="desiredState">Die vorhergesagten Status der Aufgaben. Die Methode wird beendet, wenn alle Aufgaben mindestens einmal dieser Status erreicht haben.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <param name="controlParams">Steuert verschiedene Einstellungen des Monitors, z. B. Verzögerung zwischen den einzelnen an.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</param>
        <summary>
            Monitore eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Auflistung erst jedes seiner Member mindestens einmal einen gewünschten Zustand erreicht.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Der Status der einzelnen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanz wird davon ausgegangen, dass autorisierende zum Zeitpunkt des Aufrufs.
            Instanzen, die bereits an die <paramref name="desiredState" /> werden ignoriert.
            Die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen in der Auflistung als schreibgeschützt behandelt werden.
            Dies bedeutet, dass bei Beendigung des Aufrufs (Timeout oder nicht) die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen sollte vor der Verwendung aktualisiert werden.
            </para>
          <para>
            Diese Methode wird asynchron ausgeführt.
            </para>
        </remarks>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die <paramref name="cancellationToken" /> wurde abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="WhenAll">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WhenAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, TimeSpan timeout, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task WhenAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.TimeSpan timeout, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function WhenAll (tasksToMonitor As IEnumerable(Of CloudTask), desiredState As TaskState, timeout As TimeSpan, Optional controlParams As ODATAMonitorControl = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.WhenAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * TimeSpan * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="taskStateMonitor.WhenAll (tasksToMonitor, desiredState, timeout, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.TaskStateMonitor/&lt;WhenAll&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor">Die Auflistung von Aufgaben zu überwachen.</param>
        <param name="desiredState">Die vorhergesagten Status der Aufgaben. Die Methode wird beendet, wenn alle Aufgaben mindestens einmal dieser Status erreicht haben.</param>
        <param name="timeout">Die maximale Zeitspanne an, diesen Aufruf, bevor ein Timeout auftritt wartet.</param>
        <param name="controlParams">Steuert verschiedene Einstellungen des Monitors, z. B. Verzögerung zwischen den einzelnen an.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</param>
        <summary>
            Monitore eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Auflistung erst jedes seiner Member mindestens einmal einen gewünschten Zustand erreicht.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Der Status der einzelnen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanz wird davon ausgegangen, dass autorisierende zum Zeitpunkt des Aufrufs.
            Instanzen, die bereits an die <paramref name="desiredState" /> werden ignoriert.
            Die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen in der Auflistung als schreibgeschützt behandelt werden.
            Dies bedeutet, dass bei Beendigung des Aufrufs (Timeout oder nicht) die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen sollte vor der Verwendung aktualisiert werden.
            </para>
          <para>
            Diese Methode wird asynchron ausgeführt.
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn die <paramref name="timeout" /> ist abgelaufen.</exception>
      </Docs>
    </Member>
  </Members>
</Type>