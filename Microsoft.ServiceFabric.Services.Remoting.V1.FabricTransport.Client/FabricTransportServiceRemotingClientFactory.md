<Type Name="FabricTransportServiceRemotingClientFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingClientFactory extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingClientFactory&#xA;Implements ICommunicationClientFactory(Of IServiceRemotingClient), IServiceRemotingClientFactory" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingClientFactory = class&#xA;    interface IServiceRemotingClientFactory&#xA;    interface ICommunicationClientFactory&lt;IServiceRemotingClient&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> , die Fabric-TCP-Transport verwendet, erstellen Sie <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" /> , kommunizieren mit zustandslosen und zustandsbehafteten Diensten über Schnittstellen, die über Remote sind <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings FabricTransportRemotingSettings = null, Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient = null, Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings FabricTransportRemotingSettings, class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient, class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.#ctor(Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings,Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings * Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient * Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory (FabricTransportRemotingSettings, callbackClient, servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="FabricTransportRemotingSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="FabricTransportRemotingSettings">
                Die Einstellungen für die Fabric-Transport. Wenn die Einstellungen nicht angegeben oder null, Standardeinstellungen ohne Sicherheit sind.
                </param>
        <param name="callbackClient">
                Der Rückruf-Client, der die Rückrufe vom Dienst empfängt.
            </param>
        <param name="servicePartitionResolver">
                Partition-Konfliktlöser auf die Dienst-Endpunkten zu beheben. Wenn nicht angegeben ist, ein Standarddienst-Konfliktlöser Partition zurückgegebenes <see cref="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" /> verwendet wird.
                </param>
        <param name="exceptionHandlers">
                Der Ausnahmehandler behandelt die Ausnahmen, die bei der Kommunikation mit dem Dienst aufgetreten.
            </param>
        <param name="traceId">
                ID, bei der Diagnose ablaufverfolgungen dieser Komponente verwendet.
            </param>
        <summary>
                Erstellt eine Fabric transportbasierte Remoting Client Dienstzuordnungsinstanz an.
            </summary>
        <remarks>
                Diese Factory verwendet einen internen Fabric Transport Ausnahmehandler zur Behandlung von Ausnahmen an den Fabric-TCP-Transportebene und eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />, zusätzlich zu den Ausnahmehandler, der an den Konstruktor angegeben. 
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ereignishandler, die ausgelöst wird, wenn ein Client an den Dienstendpunkt verbunden ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of IServiceRemotingClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ereignishandler, die ausgelöst wird, wenn ein Client von der Dienstendpunkt getrennt ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V1-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;</ReturnType>
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
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory/&lt;Microsoft-ServiceFabric-Services-Communication-Client-ICommunicationClientFactory&lt;Microsoft-ServiceFabric-Services-Remoting-V1-Client-IServiceRemotingClient&gt;-GetClientAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;</ReturnType>
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
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ICommunicationClientFactory&lt;IServiceRemotingClient&gt;.ReportOperationExceptionAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient&gt;.ReportOperationExceptionAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory.Microsoft#ServiceFabric#Services#Communication#Client#ICommunicationClientFactory&lt;Microsoft#ServiceFabric#Services#Remoting#V1#Client#IServiceRemotingClient&gt;#ReportOperationExceptionAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />
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