<Type Name="ActorProxyFactory" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory">
  <TypeSignature Language="C#" Value="public class ActorProxyFactory : Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorProxyFactory extends System.Object implements class Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorProxyFactory&#xA;Implements IActorProxyFactory" />
  <TypeSignature Language="F#" Value="type ActorProxyFactory = class&#xA;    interface IActorProxyFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Factoryklasse zum Erstellen eines Proxys für die remote Akteur-Objekte dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory retrySettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="retrySettings">Wiederholen Sie die Einstellungen für das Remoteobjekt Aufrufe von Proxy.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackClient, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient, Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient,Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">Factorymethode zum Erstellen von Client-Kommunikation-Remoting-Factory.</param>
        <param name="retrySettings">Wiederholen Sie die Einstellungen für das Remoteobjekt Aufrufe von Proxy.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> -Klasse unter Verwendung von V1 Remoting Client-Factory.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorProxyFactory (Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; createServiceRemotingClientFactory, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.#ctor(System.Func{Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory},Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createServiceRemotingClientFactory As Func(Of IServiceRemotingCallbackMessageHandler, IServiceRemotingClientFactory), Optional retrySettings As OperationRetrySettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory : Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt; * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings -&gt; Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" Usage="new Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory (createServiceRemotingClientFactory, retrySettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createServiceRemotingClientFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory&gt;" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
      </Parameters>
      <Docs>
        <param name="createServiceRemotingClientFactory">Factorymethode zum Erstellen von Client-Kommunikation-Remoting-Factory.</param>
        <param name="retrySettings">Wiederholen Sie die Einstellungen für das Remoteobjekt Aufrufe von Proxy.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory" /> -Klasse unter Verwendung von Client-V2-Remoting-Factory.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert. Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.
            </typeparam>
        <param name="serviceUri">Der URI des Diensts Akteur.</param>
        <param name="actorId">Akteur-Id des Objekts Akteur Proxy. Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</param>
        <param name="listenerName">
            Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.
            Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.
            </param>
        <summary>
            Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.
            </summary>
        <returns>Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorProxy&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public TActorInterface CreateActorProxy&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TActorInterface CreateActorProxy&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)&#xA;override this.CreateActorProxy : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="actorProxyFactory.CreateActorProxy (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorProxy``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TActorInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActorInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert. Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.
            </typeparam>
        <param name="actorId">Akteur-Id des Objekts Akteur Proxy. Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</param>
        <param name="applicationName">
            Der Name der Service Fabric-Anwendung, die der Akteur-Dienst hostet die Akteur-Objekte enthält.
            Dieser Parameter kann null sein, wenn der Client als Teil der gleichen Service Fabric-Anwendung ausgeführt wird. Weitere Informationen finden Sie in den Hinweisen. 
            </param>
        <param name="serviceName">
            Name des Service Fabric-Dienstes, je nach Konfiguration durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> auf die Akteur-Implementierung.
            Standardmäßig ist der Name des Diensts nicht mit dem Namen der Akteur-Schnittstelle abgeleitet. Jedoch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> ist erforderlich, wenn ein Akteur mehr als ein Akteur Schnittstellen implementiert oder eine Akteur-Schnittstelle wird von einer anderen Akteur-Schnittstelle abgeleitet, wie die Festlegung der ServiceName automatisch hergestellt werden kann.
            </param>
        <param name="listenerName">
            Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.
            Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.
            </param>
        <summary>
            Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.
            </summary>
        <returns>Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, class Microsoft.ServiceFabric.Actors.ActorId actorId, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * Microsoft.ServiceFabric.Actors.ActorId * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, actorId, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</typeparam>
        <param name="serviceUri">URI des Diensts Akteur für die Verbindung.</param>
        <param name="actorId">Die ID des Akteurs. Der erstellte Proxy wird mit der Partition des hosting mit dieser Id Akteur Akteur-Diensts verbunden sein.</param>
        <param name="listenerName">
            Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.
            Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.
            </param>
        <summary>
            Erstellen Sie einen Proxy mit dem Akteur-Dienst, der Hosten der angegebenen Akteur-Id und der Dienstschnittstelle angegebenen Typ implementieren.
            </summary>
        <returns>Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und TServiceInterface.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateActorServiceProxy&lt;TServiceInterface&gt;">
      <MemberSignature Language="C#" Value="public TServiceInterface CreateActorServiceProxy&lt;TServiceInterface&gt; (Uri serviceUri, long partitionKey, string listenerName = null) where TServiceInterface : Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !!TServiceInterface CreateActorServiceProxy&lt;(class Microsoft.ServiceFabric.Services.Remoting.IService) TServiceInterface&gt;(class System.Uri serviceUri, int64 partitionKey, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateActorServiceProxy(Of TServiceInterface As IService) (serviceUri As Uri, partitionKey As Long, Optional listenerName As String = null) As TServiceInterface" />
      <MemberSignature Language="F#" Value="abstract member CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)&#xA;override this.CreateActorServiceProxy : Uri * int64 * string -&gt; 'ServiceInterface (requires 'ServiceInterface :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="actorProxyFactory.CreateActorServiceProxy (serviceUri, partitionKey, listenerName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Client.IActorProxyFactory.CreateActorServiceProxy``1(System.Uri,System.Int64,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TServiceInterface</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TServiceInterface">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TServiceInterface">Die Dienstschnittstelle, die vom Akteur Dienst implementiert wird.</typeparam>
        <param name="serviceUri">URI des Diensts Akteur für die Verbindung.</param>
        <param name="partitionKey">Der Schlüssel des für die Verbindung der Akteur-Dienstpartition.</param>
        <param name="listenerName">
            Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.
            Jedoch möglich ist, mehrere Listener einen Akteur-Dienst konfigurieren, gibt der ListenerName-Parameter den Namen des Listeners für die Verbindung an.
            </param>
        <summary>
            Erstellen Sie einen Proxy mit dem Akteur-Dienst, der Hosten der angegebenen Akteur-Id und der Dienstschnittstelle angegebenen Typ implementieren.
            </summary>
        <returns>Ein Dienstobjekt für den Proxy, implementiert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.IServiceProxy" /> und TServiceInterface.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>