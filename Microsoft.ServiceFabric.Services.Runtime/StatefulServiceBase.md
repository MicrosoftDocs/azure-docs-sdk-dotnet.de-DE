<Type Name="StatefulServiceBase" FullName="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase">
  <TypeSignature Language="C#" Value="public abstract class StatefulServiceBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatefulServiceBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatefulServiceBase" />
  <TypeSignature Language="F#" Value="type StatefulServiceBase = class&#xA;    interface IStatefulUserServiceReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Basisklasse für statusbehaftete zuverlässige Dienst Microsoft Service Fabric-basiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatefulServiceBase (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.IStateProviderReplica2 stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.IStateProviderReplica2)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatefulServiceContext, stateProviderReplica As IStateProviderReplica2)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.IStateProviderReplica2 -&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase (serviceContext, stateProviderReplica)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            Ein <see cref="T:System.Fabric.StatefulServiceContext" /> beschreibt den Dienstkontext, der er Informationen wie Replikat-ID, Partitions-ID und Name des Diensts bereitstellt.
            </param>
        <param name="stateProviderReplica">
            Ein <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica2" /> einem zuverlässigen Zustand Anbieter Replikat darstellt.
            </param>
        <summary>
            Erstellt einen neuen zustandsbehafteten Dienst.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync backupDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
      </Parameters>
      <Docs>
        <param name="backupDescription">
            Ein <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> , beschreibt die Anforderung für die Sicherung.
            </param>
        <summary>
            Führt eine Sicherung alle zuverlässige Status, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupDescription backupDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupDescription backupDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.BackupAsync(Microsoft.ServiceFabric.Data.BackupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : Microsoft.ServiceFabric.Data.BackupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.BackupAsync (backupDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDescription" Type="Microsoft.ServiceFabric.Data.BackupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDescription">Ein <see cref="T:Microsoft.ServiceFabric.Data.BackupDescription" /> , beschreibt die Anforderung für die Sicherung.</param>
        <param name="timeout">Das Timeout für diesen Vorgang.</param>
        <param name="cancellationToken">Das Abbruchtoken, das dient zum Überwachen von abbruchanforderungen.</param>
        <summary>
            Führt eine Sicherung alle zuverlässige Status, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.
            Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.
            Darüber hinaus wird Sicherung als fehlgeschlagen markiert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatefulServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatefulServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatefulServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatefulServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatefulServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Dienstkontext, in denen dieses zustandsbehafteten Dienst unter ab.
            Es enthält Informationen wie die Replikat-ID, Partitions-ID, Name des Diensts usw.
            </summary>
        <value>
            Ein <see cref="T:System.Fabric.StatefulServiceContext" /> beschreibt den Dienstkontext, der er Informationen wie Replikat-ID, Partitions-ID und Name des Diensts bereitstellt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceReplicaListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceReplicaListeners () As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;&#xA;override this.CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;" Usage="statefulServiceBase.CreateServiceReplicaListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.CreateServiceReplicaListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überschreiben Sie diese Methode, um die kommunikationsüberwachungen für das Replikat Service angeben. Die Endpunkte, die vom Listener Kommunikation zurückgegeben werden als JSON-Zeichenfolge der ListenerName, Endpunkt Zeichenfolgenpaare wie gespeichert. 
            <code>{"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</code><para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>Liste der<see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" /></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statefulServiceBase.GetAddresses " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Liste der alle Adressen für diese dienstreplikats als (ListenerName Endpunkt) Schlüssel-Wert-Paar.
            </summary>
        <returns>
            Ein <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> Liste der Adressen als (ListenerName Endpunkt) mit Schlüssel / Wert-Paar.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statefulServiceBase.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnAbort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Die Benachrichtigung, dass der Dienst abgebrochen wird. Coredispatcher möglicherweise wie der Abbruch nicht im Pfad Abbruch gewartet wird gleichzeitig mit der Ausführung dieser Methode wird ausgeführt. 
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">Neue <see cref="T:System.Fabric.ReplicaRole" /> für dieses Replikat Dienst.</param>
        <param name="cancellationToken">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</param>
        <summary>
            Diese Methode wird aufgerufen, wenn die Rolle des Replikats ändert, und es ist der letzte Schritt vor dem Abschluss <see cref="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.
            Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass ChangeRole für dieses Replikat interne Komponenten abgeschlossen wurde.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task" /> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</param>
        <summary>
            Diese Methode wird als abschließenden Schritt schließen Sie den Dienst ordnungsgemäß aufgerufen.
            Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass für dieses Replikat interne Komponenten schließen abgeschlossen wurde.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype Microsoft.ServiceFabric.Data.RestoreContext restoreCtx, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnDataLossAsync(Microsoft.ServiceFabric.Data.RestoreContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : Microsoft.ServiceFabric.Data.RestoreContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="statefulServiceBase.OnDataLossAsync (restoreCtx, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreCtx" Type="Microsoft.ServiceFabric.Data.RestoreContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreCtx">
            Ein <see cref="T:Microsoft.ServiceFabric.Data.RestoreContext" /> zum Wiederherstellen des Diensts verwendet werden.
            </param>
        <param name="cancellationToken">
          <see cref="T:System.Threading.CancellationToken" />zum Überwachen von abbruchanforderungen.
            </param>
        <summary>
            Diese Methode wird während der potenziellen Datenverlust aufgerufen. Sie können diese Methode, um den Dienst bei einem Datenverlust wiederherzustellen überschreiben.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.
            "True" gibt an, dass der Zustand wiederhergestellt wurde.
            False gibt an, dass das Replikat Zustand nicht geändert wurde.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnOpenAsync (openMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <see cref="T:System.Fabric.ReplicaOpenMode" />für dieses Replikat Dienst.</param>
        <param name="cancellationToken">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</param>
        <summary>
            Diese Methode wird aufgerufen, wenn das Replikat wurde geöffnet, und es der letzte Schritt ist des Öffnens des Diensts.
            Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass für dieses Replikat interne Komponenten öffnen abgeschlossen wurde.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <see cref="T:System.Threading.CancellationToken" />zum Überwachen von abbruchanforderungen.
            </param>
        <summary>
            Diese Methode wird aufgerufen, wenn der Replikatstatus über den Service Wiederherstellung erfolgreich wiederhergestellt wurde
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatefulServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatefulServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatefulServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatefulServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatefulServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Dienstpartition, welche aktuellen Dienst Replikat gehört. 
            </summary>
        <value>
            Ein <see cref="T:System.Fabric.IStatefulServicePartition" /> , der die Partition, zu der dieser Dienst Replikat gehört, darstellt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statefulServiceBase.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatefulUserServiceReplica.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken, das zum Überwachen von abbruchanforderungen.</param>
        <summary>
            Diese Methode wird als eine Verarbeitungsschleife implementiert und wird nur aufgerufen werden, wenn das Replikat Primär mit Schreibstatus ist.
            Überschreiben Sie diese Methode mit der Anwendungslogik. 
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>
            Vergewissern Sie sich überschreiben, gelten folgende Richtlinien <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description> stellen Sie sicher, dass <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> berücksichtigt wird und nachdem es signalisiert worden ist, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> als ordnungsgemäß beendet So bald wie möglich. Bitte beachten Sie, dass bei <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> hat die vorgesehene Arbeit, er muss nicht warten <paramref name="cancellationToken" /> auf die Signalisierung und ordnungsgemäß zurückgeben kann. </description></item><item><description>Service Fabric-Laufzeit behandelt nicht alle Escapezeichen aus Ausnahme(n) <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. Wenn eine nicht behandelte Ausnahme aus Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, dauert Service Fabric-Laufzeit folgende Aktionen aus: <list type="bullet"> <item> <description> Wenn eine <see cref="T:System.Fabric.FabricException" /> (oder eines seiner abgeleiteten Ausnahme) schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Common Language Runtime wird dieses Replikat Dienst neu gestartet. Eine Warnung Health werden im Service Fabric-Explorer enthält Informationen zu nicht behandelte Ausnahme angezeigt werden. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric Runtime Abbruch angefordert hat, durch Signalisieren <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Runtime diese Ausnahme behandelt und betrachtet er als ordnungsgemäße Beendigung von <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric-Laufzeit nicht Abbruch durch Signalisieren angefordert hat <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />, wird der Prozess, der diesem Dienst Replikat gehostet wird nach unten versetzt. Dadurch wird anderen dienstreplikate beeinträchtigt, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item><item><description>Wenn eine Ausnahme eines anderen Typs von Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" /> und klicken Sie dann der Prozess, der diesem Dienst Replikat gehostet wird heruntergefahren wird. Dadurch wird anderen dienstreplikate beeinträchtigt, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item></list></description></item></list><para>Wegen eines Fehlers beim entsprechen, diese Richtlinien können dazu führen, dass ein Failover, Neukonfiguration oder Aktualisierung des Diensts bei hängen bleiben und Verfügbarkeit Ihres Diensts auswirken können.</para></remarks>
      </Docs>
    </Member>
  </Members>
</Type>