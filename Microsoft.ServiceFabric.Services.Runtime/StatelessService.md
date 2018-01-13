<Type Name="StatelessService" FullName="Microsoft.ServiceFabric.Services.Runtime.StatelessService">
  <TypeSignature Language="C#" Value="public abstract class StatelessService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatelessService extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatelessService" />
  <TypeSignature Language="F#" Value="type StatelessService = class&#xA;    interface IStatelessUserServiceInstance" />
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
            Stellt die Microsoft Service Fabric basierend zustandslose zuverlässigen Dienst-Basisklasse. Ableiten von dieser Klasse zum Implementieren eines Microsoft Service Fabric-basierten zustandslosen zuverlässige-Diensts.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatelessService (System.Fabric.StatelessServiceContext serviceContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatelessServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.#ctor(System.Fabric.StatelessServiceContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatelessServiceContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatelessService : System.Fabric.StatelessServiceContext -&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatelessService serviceContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatelessServiceContext" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            Ein <see cref="T:System.Fabric.StatelessServiceContext" /> , beschreibt der Kontext.
            </param>
        <summary>
            Erstellt eine neue <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" />-Instanz.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatelessServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatelessServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatelessServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatelessServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatelessServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Dienstkontext, in denen diese statusfreien Dienst unter ab. Es enthält Informationen wie InstanceId, PartitionId usw. ServiceName.
            </summary>
        <value>
            Ein <see cref="T:System.Fabric.StatelessServiceContext" /> , beschreibt der Kontext.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceInstanceListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.CreateServiceInstanceListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceInstanceListeners () As IEnumerable(Of ServiceInstanceListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;&#xA;override this.CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;" Usage="statelessService.CreateServiceInstanceListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.CreateServiceInstanceListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überschreiben Sie diese Methode, um die kommunikationsüberwachungen für die Instanz angeben. Die Endpunkte zurückgegeben, die für die Kommunikation des Listeners als JSON-Zeichenfolge der ListenerName gespeichert sind, wie Zeichenfolgenpaar Endpunkt {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>Liste der ServiceInstanceListeners</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statelessService.GetAddresses " />
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
            Ruft die Liste der alle Adressen für diese Dienstinstanz als (ListenerName Endpunkt) Schlüssel-Wert-Paar.
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statelessService.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnAbort</InterfaceMember>
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
            Benachrichtigung, dass der Dienst abgebrochen wird.  Coredispatcher möglicherweise wie der Abbruch nicht im Pfad Abbruch gewartet wird gleichzeitig mit der Ausführung dieser Methode wird ausgeführt.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
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
        <param name="cancellationToken">Abbruchtoken, das zum Überwachen von abbruchanforderungen bereitgestellt.</param>
        <summary>
            Diese Methode wird als abschließenden Schritt schließen Sie den Dienst aufgerufen.
            Überschreiben Sie diese Methode, um benachrichtigt zu werden, dass für diese Instanz interne Komponenten schließen abgeschlossen wurde.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnOpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnOpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnOpenAsync(System.Threading.CancellationToken)</InterfaceMember>
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
            Diese Methode wird als abschließenden Schritt des Öffnens des Diensts aufgerufen.
            Überschreiben Sie diese Methode, um benachrichtigt zu werden, die für diese Instanz interne Komponenten öffnen abgeschlossen ist.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatelessServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatelessServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatelessServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatelessServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatelessServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dienstpartition auf dem aktuellen Dienst Instanz gehört. 
            </summary>
        <value>
            Ein <see cref="T:System.Fabric.IStatelessServicePartition" /> , der die Partition, zu der dieser Dienst Replikat gehört, darstellt.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
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
            Dienste, die einen Hintergrundtask aus, die ausgeführt wird, wenn der Dienst hochgefahren, zu implementieren möchten, sollten diese Methode mit ihrer Logik überschreiben.
            <para>Informationen zum Lebenszyklus zuverlässige Dienste finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>
            Vergewissern Sie sich überschreiben, gelten folgende Richtlinien <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description> stellen Sie sicher, dass <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> berücksichtigt wird und nachdem es signalisiert worden ist, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> als ordnungsgemäß beendet So bald wie möglich. Bitte beachten Sie, dass bei <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> hat die vorgesehene Arbeit, er muss nicht warten <paramref name="cancellationToken" /> auf die Signalisierung und ordnungsgemäß zurückgeben kann. </description></item><item><description>Service Fabric-Laufzeit behandelt nicht alle Escapezeichen aus Ausnahme(n) <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. Wenn eine nicht behandelte Ausnahme aus Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, dauert Service Fabric-Laufzeit folgende Aktionen aus: <list type="bullet"> <item> <description> Wenn eine <see cref="T:System.Fabric.FabricException" /> (oder eines seiner abgeleiteten Ausnahme) schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Common Language Runtime löscht diese Instanz und eine neue Instanz erstellt werden. Eine Warnung Health werden im Service Fabric-Explorer enthält Informationen zu nicht behandelte Ausnahme angezeigt werden. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric Runtime Abbruch angefordert hat, durch Signalisieren <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric Runtime diese Ausnahme behandelt und betrachtet er als ordnungsgemäße Beendigung von <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description>Wenn ein <see cref="T:System.OperationCanceledException" /> schützt aus <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> und Service Fabric-Laufzeit nicht Abbruch durch Signalisieren angefordert hat <paramref name="cancellationToken" /> übergeben <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, der Prozess, der dieser Dienstinstanz hostet unten geschaltet wird. Dies wirkt sich alle Dienstinstanzen, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item><item><description>Wenn eine Ausnahme eines anderen Typs von Escapevorgang <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> und klicken Sie dann der Prozess, der dieser Dienstinstanz hostet heruntergefahren wird. Dies wirkt sich alle Dienstinstanzen, die vom gleichen Prozess gehostet werden. Die Details von nicht behandelten Ausnahmen können in der Windows-Ereignisanzeige angezeigt werden. </description></item></list></description></item></list><para>Wegen eines Fehlers beim entsprechen, diese Richtlinien können dazu führen, dass ein Failover, Neukonfiguration oder Aktualisierung des Diensts bei hängen bleiben und Verfügbarkeit Ihres Diensts auswirken können.</para></remarks>
      </Docs>
    </Member>
  </Members>
</Type>