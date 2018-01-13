<Type Name="ICommunicationClientFactory&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public interface ICommunicationClientFactory&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationClientFactory`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationClientFactory(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TCommunicationClient">Kommunikation-Clienttyp</typeparam>
    <summary>
            Definiert die Schnittstelle, die implementiert werden muss, um eine Factory für die Kommunikation von Clients mit einem Service Fabric-Dienst kommuniziert bereitzustellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ereignishandler, die ausgelöst wird, wenn die Kommunikation-Client eine Verbindung zum Dienstendpunkt herstellt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ereignishandler, die ausgelöst wird, wenn der Dienstendpunkt die Kommunikation vom Client getrennt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="iCommunicationClientFactory.GetClientAsync (previousRsp, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">Vorherige ResolvedServicePartition-Wert</param>
        <param name="targetReplicaSelector">Gibt an, welches Replikat in der Partition, die durch den Partitionsschlüssel identifiziert, die Clients muss eine Verbindung mit</param>
        <param name="listenerName">Gibt an, welche Listener im Endpunkt des ausgewählten Replikats an, zu dem der Client eine eine Verbindung herstellen soll</param>
        <param name="retrySettings">Gibt die wiederholungsrichtlinie, die für Ausnahmen, die verwendet werden soll, die auftreten, wenn den Client zu erstellen.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Erneut löst eine Partition des angegebenen Diensts, die eine oder mehrere kommunikationsüberwachungen enthält, und gibt einen Client für die Kommunikation mit dem Endpunkt, der angegebene ListenerName entspricht. 
            
            Der Endpunkt des Diensts besitzt das Format - {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis der Aufgabe ist die CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) Objekt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="iCommunicationClientFactory.GetClientAsync (serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">URI des Diensts aufgelöst</param>
        <param name="partitionKey">Schlüssel, die Partition zum Auflösen identifiziert</param>
        <param name="targetReplicaSelector">Gibt an, welches Replikat in der Partition, die durch den Partitionsschlüssel identifiziert, die Clients muss eine Verbindung mit</param>
        <param name="listenerName">Gibt an, welche Listener im Endpunkt des ausgewählten Replikats an, zu dem der Client eine eine Verbindung herstellen soll</param>
        <param name="retrySettings">Gibt die wiederholungsrichtlinie, die für Ausnahmen, die verwendet werden soll, die auftreten, wenn den Client zu erstellen.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Löst eine Partition des angegebenen Dienstes, einen oder mehrere kommunikationsüberwachungen auf und gibt einen Client für die Kommunikation mit dem Endpunkt, der angegebene ListenerName entspricht. 
            
            Der Endpunkt des Diensts besitzt das Format - {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis der Aufgabe ist die CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) Objekt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync (TCommunicationClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync(!TCommunicationClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;" Usage="iCommunicationClientFactory.ReportOperationExceptionAsync (client, exceptionInformation, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">Kommunikationsclient</param>
        <param name="exceptionInformation">Informationen über die Ausnahme, die während der Kommunikation mit dem Dienst aufgetreten sind.</param>
        <param name="retrySettings">Gibt die wiederholungsrichtlinie, die für die gemeldeten Ausnahmebehandlung verwendet werden soll.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Behandelt die Ausnahmen, die in der CommunicationClient auftreten, wenn eine Nachricht an den Dienst senden
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis des Vorgangs ist ein <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> -Objekt, das auf die wiederholungsrichtlinie für diese Ausnahme hin.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>