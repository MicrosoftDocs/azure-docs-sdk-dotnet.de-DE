<Type Name="CloudPool" FullName="Microsoft.Azure.Batch.CloudPool">
  <TypeSignature Language="C#" Value="public class CloudPool : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudPool extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudPool" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudPool&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudPool = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;PoolAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Dieser Pool in der Azure Batch-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Batch.Common.AllocationState&gt;" Usage="Microsoft.Azure.Batch.CloudPool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.Batch.Common.AllocationState" /> gibt an welchem Knoten Zuordnung Aktivitäten für den Pool stattfinden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit, an dem der Pool erlangt seinem aktuellen hat <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Anwendungslizenzen der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Liste der Anwendungslizenzen muss es sich um eine Teilmenge der verfügbaren Batch Dienstlizenzen Anwendung sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Anwendungspaketen auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoScaleEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoScaleEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Poolgröße gemäß automatisch anpassen, sollten die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Bei "true", die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> ist eine erforderliche Eigenschaft, die der Pool ändert automatisch entsprechend der Formel und <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> muss null sein.</para>
          <para>Wenn "false" eines der <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> Eigenschaften ist erforderlich.</para>
          <para>Der Standardwert ist „false“.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Zeitintervall an, passen Sie die Poolgröße gemäß automatisch an die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert beträgt 15 Minuten. Der minimal zulässige Wert beträgt 5 Minuten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Formel für die gewünschte Anzahl von Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Für das Schreiben von Formeln für automatische Skalierung finden Sie unter https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/. Diese Eigenschaft ist erforderlich, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> festgelegt ist auf "true". Sie muss null sein, wenn AutoScaleEnabled auf "false" festgelegt ist.</para>
          <para>Die Formel wird auf Gültigkeit überprüft, bevor der Pool erstellt wird. Wenn die Formel nicht gültig ist, wird eine Ausnahme ausgelöst, wenn Sie versuchen, einen commit für die <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun AutoScaleRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Batch.AutoScaleRun" Usage="Microsoft.Azure.Batch.CloudPool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ergebnisse und Fehler aus der letzten Ausführung der <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersion">
      <MemberSignature Language="C#" Value="public void ChangeOSVersion (string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ChangeOSVersion(string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersion(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ChangeOSVersion (targetOSVersion As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersion : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.ChangeOSVersion (targetOSVersion, additionalBehaviors)" />
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
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="targetOSVersion">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Ändert die Version des Betriebssystems von diesem Pool.
            </summary>
        <remarks>
          <para>Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.  Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.  Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</para>
          <para>Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</para>
          <para>Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.  Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</para>
          <para>Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern. Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersionAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeOSVersionAsync (string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ChangeOSVersionAsync(string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ChangeOSVersionAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersionAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.ChangeOSVersionAsync (targetOSVersion, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="targetOSVersion">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ändert die Version des Betriebssystems von diesem Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Während des Vorgangs der Änderung BS-Version durchläuft der Batch-Dienst die Knoten des Pools, ändern die Betriebssystemversion der Serverknoten an.  Wenn Compute-Knoten ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und in die Warteschlange zur später (oder auf einem anderen Serverknoten) erneut ausgeführt werden.  Der Knoten wird nicht verfügbar sein, bis die versionsänderung abgeschlossen ist.</para>
          <para>Der Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb getroffen werden, um ihre Version des Betriebssystems geändert haben. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, ändern alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); der Vorgang kann daher im Pool wird vorübergehend nicht verfügbar, um Aufgaben auszuführen, führen.</para>
          <para>Wenn Sie ein Betriebssystem-versionsänderung anfordern, ändert sich der Pool Zustand zu <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.  Wenn alle Knoten haben, ändern die Version zu berechnen, wird der Poolstatus zur zurück <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</para>
          <para>Während die versionsänderung, den Pool der läuft <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> gibt die Version des Betriebssystems, den Knoten aus, ändern und <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> gibt die Version des Betriebssystems, den Knoten zu ändern. Nachdem die Änderung abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird.</para>
          <para>Vorgang zum Ändern des Version wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" /> für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Commit additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Führt einen Commit für diese <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.
            </summary>
        <remarks>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;CommitAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Führt einen Commit für diese <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Commitvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChanges">
      <MemberSignature Language="C#" Value="public void CommitChanges (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CommitChanges(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.CommitChanges(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CommitChanges (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CommitChanges : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.CommitChanges additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Führt einen Commit für alle ausstehenden Änderungen dieser <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.
            </summary>
        <remarks>
          <para>
            Aktualisiert ein vorhandenes <see cref="T:Microsoft.Azure.Batch.CloudPool" /> auf der Batch-Dienst, indem Sie seine Eigenschaften mit den Eigenschaften dieser ersetzen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> die geändert wurden.
            Unveränderte Eigenschaften werden ignoriert.
            Alle Änderungen seit der letzten Ausführung dieser Entität aus der Batch-Dienst abgerufen wurde (entweder über <see cref="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, oder <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) angewendet werden.
            Eigenschaften, die auf null wird explizit festgelegt sind, wird eine Ausnahme ausgelöst, da der Batch-Dienst nicht teilweise Updates unterstützt, die eine Eigenschaft auf null festgelegt.
            Wenn Sie eine Eigenschaft auf null festgelegt, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Methode.
            </para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitChangesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitChangesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitChangesAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.CommitChangesAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;CommitChangesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Führt einen Commit für alle ausstehenden Änderungen dieser <see cref="T:Microsoft.Azure.Batch.CloudPool" /> an den Azure Batch-Dienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Aktualisiert ein vorhandenes <see cref="T:Microsoft.Azure.Batch.CloudPool" /> auf der Batch-Dienst, indem Sie seine Eigenschaften mit den Eigenschaften dieser ersetzen <see cref="T:Microsoft.Azure.Batch.CloudPool" /> die geändert wurden.
            Unveränderte Eigenschaften werden ignoriert.
            Alle Änderungen seit der letzten Ausführung dieser Entität aus der Batch-Dienst abgerufen wurde (entweder über <see cref="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, oder <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) angewendet werden.
            Eigenschaften, die auf null wird explizit festgelegt sind, wird eine Ausnahme ausgelöst, da der Batch-Dienst nicht teilweise Updates unterstützt, die eine Eigenschaft auf null festgelegt.
            Wenn Sie eine Eigenschaft auf null festzulegen, verwenden <see cref="M:Microsoft.Azure.Batch.CloudPool.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.
            </para>
          <para>Dieser Vorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt der Erstellung für den Pool an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicated : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CurrentDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete after 05/2017, use CurrentDedicatedComputeNodes instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft ist ein Alias für <see cref="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" /> und wird nur für Abwärtskompatibilität unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedComputeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedComputeNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CurrentDedicatedComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der dedizierten Serverknoten, die derzeit im Pool ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityComputeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CurrentLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityComputeNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.CloudPool.CurrentLowPriorityComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Serverknoten mit niedriger Priorität, die derzeit im Pool ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Mit niedriger Priorität Serverknoten die vorweggenommen haben sind in dieser Anzahl enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />
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
            Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.CloudPool" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</para>
          <para>Änderungen werden in der Reihenfolge der Auflistung angewendet. Der letzte write Wins.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Delete additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Löscht diesen Pool an.
            </summary>
        <remarks>
          <para>Der Löschvorgang fordert, dass der Pool gelöscht werden.  Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.
            Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</para>
          <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Löscht diesen Pool an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Löschvorgang fordert, dass der Pool gelöscht werden.  Die Anforderung setzt den Pool in der <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> Zustand.
            Der Batch-Dienst wird requeue alle ausgeführten Aufgaben und das tatsächliche Pool löschen, ohne weitere Clientaktion ausführen.</para>
          <para>Der Löschvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public void DisableAutoScale (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableAutoScale(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScale(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableAutoScale (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScale : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.DisableAutoScale additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Deaktiviert die automatische Skalierung für diesen Pool.
            </summary>
        <remarks>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScaleAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAutoScaleAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAutoScaleAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.DisableAutoScaleAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScaleAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.DisableAutoScaleAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;DisableAutoScaleAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Deaktiviert die automatische Skalierung für diesen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Der Deaktivierungsvorgang für die automatische Skalierung wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public void EnableAutoScale (string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableAutoScale(string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScale(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableAutoScale (Optional autoscaleFormula As String = null, Optional autoscaleEvaluationInterval As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.EnableAutoScale (autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors)" />
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
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <param name="autoscaleEvaluationInterval">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll. Der Standardwert beträgt 15 Minuten. Der minimal zulässige Wert beträgt 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Ermöglicht die automatische Skalierung für diesen Pool.
            </summary>
        <remarks>
          <para>Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird. Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</para>
          <para>Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAutoScaleAsync (string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAutoScaleAsync(string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScaleAsync : string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.EnableAutoScaleAsync (autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;EnableAutoScaleAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <param name="autoscaleEvaluationInterval">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll. Der Standardwert beträgt 15 Minuten. Der minimal zulässige Wert beträgt 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ermöglicht die automatische Skalierung für diesen Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird. Wenn die Formel nicht gültig ist, eine Ausnahme auftritt ist.</para>
          <para>Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird.</para>
          <para>Der Vorgang zum Aktivieren der automatischen Skalierung wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudPool.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das ETag für den Pool an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale (string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale(string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScale(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function EvaluateAutoScale (autoscaleFormula As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScale : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.AutoScaleRun" Usage="cloudPool.EvaluateAutoScale (autoscaleFormula, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula">Die Formel für den Pool ausgewertet werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für diesen Pool Skalierung.  Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.
            </summary>
        <returns>Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für diesen Pool.</returns>
        <remarks>
          <para>Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.  Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScale(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</para>
          <para>Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync (string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync(string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.EvaluateAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScaleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;" Usage="cloudPool.EvaluateAutoScaleAsync (autoscaleFormula, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;EvaluateAutoScaleAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="autoscaleFormula">Die Formel für den Pool ausgewertet werden soll.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für diesen Pool Skalierung.  Dies ist in erster Linie für eine Formel für automatische Skalierung überprüfen, da sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool.
            </summary>
        <returns>Das Ergebnis der Auswertung der <paramref name="autoscaleFormula" /> für diesen Pool.</returns>
        <remarks>
          <para>Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird.  Verwenden Sie zum Anwenden der Formel für den Pool <see cref="M:Microsoft.Azure.Batch.CloudPool.EnableAutoScaleAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
          <para>Diese Methode ändert sich nicht auf einem beliebigen Zustand des Pools und hat keinen Einfluss auf die <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> oder <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</para>
          <para>Die Evaluate-Vorgänge werden asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNode GetComputeNode (string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNode GetComputeNode(string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.GetComputeNode(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetComputeNode : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.ComputeNode" Usage="cloudPool.GetComputeNode (computeNodeId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool abgerufen.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Ruft den angegebenen Serverknoten aus diesem Pool ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</returns>
        <remarks>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.GetComputeNodeAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync (string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync(string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.GetComputeNodeAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetComputeNodeAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="cloudPool.GetComputeNodeAsync (computeNodeId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool abgerufen.</param>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft den angegebenen Serverknoten aus diesem Pool ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> mit Informationen über den angegebenen Compute-Knoten.</returns>
        <remarks>Das Abrufen des Knotens wird asynchron ausgeführt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Id des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterComputeNodeCommunicationEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; InterComputeNodeCommunicationEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property InterComputeNodeCommunicationEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.InterComputeNodeCommunicationEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.InterComputeNodeCommunicationEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der Pool direkten Kommunikation zwischen der Serverknoten zulässt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Aktivieren der Kommunikation zwischen den Knoten schränkt die maximale Größe des Pools aufgrund von Einschränkungen der Bereitstellung auf den Knoten des Pools. Dies kann im Pool nicht die gewünschte Größe erreichen führen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt den letzten Änderung des Pools an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListComputeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ListComputeNodes(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListComputeNodes : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="cloudPool.ListComputeNodes (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" /> und <paramref name="detailLevel" />.</param>
        <summary>
            Listet die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> von diesem Pool.
            </summary>
        <returns>Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die asynchron oder synchron Auflisten von Computeknoten verwendet werden kann.</returns>
        <remarks>Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Knoten aus dem Batch-Dienst abgerufen.
            Datenabruf ist nicht atomaren; Knoten werden in Seiten während der Enumeration der Auflistung abgerufen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerComputeNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerComputeNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerComputeNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.MaxTasksPerComputeNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerComputeNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerComputeNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.MaxTasksPerComputeNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Aufgaben, die gleichzeitig auf einem einzelnen Serverknoten im Pool ausgeführt werden können.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist 1. Der maximale Wert dieser Einstellung hängt von der Größe der Serverknoten im Pool (die <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" /> Eigenschaft).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.CloudPool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Netzwerkkonfiguration des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Die Detailstufe für die Aktualisierung.  Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.CloudPool" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RefreshAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Die Detailstufe für die Aktualisierung.  Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.CloudPool" />.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Aktualisierungsvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNode">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Entfernt den angegebenen Serverknoten aus diesem Pool.
            </summary>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (computeNodes As IEnumerable(Of ComputeNode), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNodes, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodes">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus diesem Pool.
            </summary>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (computeNodeIds As IEnumerable(Of String), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodeIds">Die Ids der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus diesem Pool.
            </summary>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.RemoveFromPool (computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Entfernt den angegebenen Serverknoten aus diesem Pool.
            </summary>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNode, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNode">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> aus dem Pool entfernen.</param>
        <param name="deallocationOption">Gibt an, wenn der Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Entfernt den angegebenen Serverknoten aus diesem Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNodes, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodes">Die <see cref="T:Microsoft.Azure.Batch.ComputeNode">Serverknoten</see> aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus diesem Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodeIds">Die Ids der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Entfernt die angegebene Serverknoten aus diesem Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.RemoveFromPoolAsync (computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudPool/&lt;RemoveFromPoolAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="computeNodeId">Die Id der Serverknoten aus dem Pool entfernen.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="resizeTimeout">Gibt das Timeout für das Entfernen von Computeknoten aus dem Pool an. Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Entfernt den angegebenen Serverknoten aus diesem Pool.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Wenn Sie mehrere Compute-Knoten aus einem Pool entfernen müssen, ist es effizienter, verwenden die <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> überladen.</para>
          <para>Sie können nur Knoten aus einem Pool entfernen bei der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> des Pools ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />. Wenn der Pool bereits Größe ist, tritt eine Ausnahme auf.</para>
          <para>Beim Entfernen von Knoten aus eines Pools, den Pool der <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert sich von <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</para>
          <para>Der Entfernungsvorgang wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public void Resize (Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Resize(valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.Resize(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Resize (Optional targetDedicatedComputeNodes As Nullable(Of Integer) = null, Optional targetLowPriorityComputeNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Resize : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.Resize (targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors)" />
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
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="targetDedicatedComputeNodes">
            Die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="targetLowPriorityComputeNodes">
            Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="resizeTimeout">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool. Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet. Der Standardwert ist 15 Minuten.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Ändert die Größe dieses Pools.
            </summary>
        <remarks>
          <para>Die Größenänderung fordert, dass der Pool Größe geändert werden.  Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.
            Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</para>
          <para>
            Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").
            Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.  Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPool(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.
            </para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.ResizeAsync(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResizeAsync (Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResizeAsync(valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.ResizeAsync(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResizeAsync : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.ResizeAsync (targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="targetDedicatedComputeNodes">
            Die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="targetLowPriorityComputeNodes">
            Die gewünschte Anzahl von mit niedriger Priorität Serverknoten im Pool.
            Mindestens eine der <paramref name="targetDedicatedComputeNodes" /> und <paramref name="targetLowPriorityComputeNodes" /> ist erforderlich.
            </param>
        <param name="resizeTimeout">Das Timeout für die Belegung der Serverknoten an den Pool oder Entfernen von Computeknoten aus dem Pool. Wenn der Pool nach diesem Zeitpunkt nicht auf die Zielgröße erreicht hat, wird die Größenänderung beendet. Der Standardwert ist 15 Minuten.</param>
        <param name="deallocationOption">
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools. Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.
            </param>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ändert die Größe dieses Pools.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Die Größenänderung fordert, dass der Pool Größe geändert werden.  Die Anforderung setzt den Pool in den <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> Zuordnungsstatus.
            Der Batch-Dienst die tatsächliche Größe ohne weitere Clientaktion durchgeführt werden, und legen Sie den Zuordnungsstatus auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> Sie abschließend auf.</para>
          <para>
            Sie können nur die Größe eines Pools bei seiner <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            Kann nicht geändert werden, die für die automatische Skalierung konfiguriert sind Pools (d. h. die <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> Eigenschaft des Pools ist "true").
            Wenn Sie die Poolgröße verringern, wählt der Batch-Dienst die Knoten aus, zu entfernen.  Rufen Sie zum Entfernen von bestimmten Knoten <see cref="M:Microsoft.Azure.Batch.CloudPool.RemoveFromPoolAsync(System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.
            </para>
          <para>Die Größenänderung wird asynchron ausgeführt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeErrors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ResizeError&gt; ResizeErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.ResizeError&gt; ResizeErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ResizeErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResizeErrors As IReadOnlyList(Of ResizeError)" />
      <MemberSignature Language="F#" Value="member this.ResizeErrors : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ResizeError&gt;" Usage="Microsoft.Azure.Batch.CloudPool.ResizeErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ResizeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Liste der Fehler aufgetreten, der letzten Größenänderung auf der <see cref="T:Microsoft.Azure.Batch.CloudPool" />. Fehler werden zurückgegeben, nur, wenn der Batch-Dienst ein Fehler beim Ändern der Größe des Pools und des Pools <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ist <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState">stetige</see>.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Timeout für die Zuweisung von Serverknoten in den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask with get, set" Usage="Microsoft.Azure.Batch.CloudPool.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen. Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.PoolState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.PoolState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of PoolState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.PoolState&gt;" Usage="Microsoft.Azure.Batch.CloudPool.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.PoolState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Status des Pools an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudPool.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem der Pool seinem aktuellen Status erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.PoolStatistics" Usage="Microsoft.Azure.Batch.CloudPool.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ressourcenauslastungsstatistiken für den Pool an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur aufgefüllt, wenn die <see cref="T:Microsoft.Azure.Batch.CloudPool" /> abgerufen wurde, mit einem <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> einschließlich das 'Statistiken für Ressourcenpools'-Attribut; andernfalls ist null.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResize">
      <MemberSignature Language="C#" Value="public void StopResize (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void StopResize(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.StopResize(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopResize (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.StopResize : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudPool.StopResize additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <summary>
            Beendet eine Größenänderung für diesen Pool an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.  Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.  Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            </para>
          <para>Dies ist ein blockierender Vorgang. Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CloudPool.StopResizeAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopResizeAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopResizeAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudPool.StopResizeAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopResizeAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudPool.StopResizeAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CloudPool.CustomBehaviors" />.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Beendet eine Größenänderung für diesen Pool an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>
            Dieser Vorgang wird ein größenänderungsvorgang für den Pool beendet.  Die Größe des Pools wird nach der Anzahl von Knoten stabilisieren, die sie sich befindet, wenn der Beendigungsvorgang abgeschlossen ist.  Während des Beendigungsvorgangs Pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> ändert zunächst in <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> , und klicken Sie dann auf <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.
            </para>
          <para>Zum Beenden der Größe Vorgang führt asynchron aus.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TargetDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicated : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TargetDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete after 05/2017, use TargetDedicatedComputeNodes instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft ist ein Alias für <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> und wird nur für Abwärtskompatibilität unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> festgelegt ist auf "true". Mindestens eine dieser Eigenschaft und <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" /> muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> lautet "false". Wenn nicht angegeben, lautet der Standardwert 0.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TargetLowPriorityComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gewünschte Anzahl von Serverknoten mit niedriger Priorität im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> festgelegt ist auf "true". Mindestens eine der <see cref="P:Microsoft.Azure.Batch.CloudPool.TargetDedicatedComputeNodes" /> und diese Eigenschaft muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> lautet "false". Wenn nicht angegeben, lautet der Standardwert 0.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.CloudPool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie Aufgaben auf Serverknoten im Pool verteilt sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudPool.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URL des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudPool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" /> des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string with get, set" Usage="Microsoft.Azure.Batch.CloudPool.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe der virtuellen Computer im Pool.  Alle virtuellen Computer in einem Pool haben die gleiche Größe.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />), finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/. Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von.</para>
          <para>Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images von virtuellen Maschinen Marketplace (mit erstellten Ressourcenpools einer <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />) finden Sie unter https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ oder https:// Azure.Microsoft.com/Documentation/articles/Virtual-Machines-Windows-sizes/. Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (z. B. STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>