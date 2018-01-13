<Type Name="ActorProxy" FullName="Microsoft.ServiceFabric.Actors.Client.ActorProxy">
  <TypeSignature Language="C#" Value="public abstract class ActorProxy : Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase, Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorProxy extends Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase implements class Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorProxy&#xA;Inherits ProxyBase&#xA;Implements IActorProxy" />
  <TypeSignature Language="F#" Value="type ActorProxy = class&#xA;    inherit ProxyBase&#xA;    interface IActorProxy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Client.IActorProxy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt die basisimplementierung für den Proxy für die remote Akteur-Objekte implementieren <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> Schnittstellen.
            Die Proxy-Objekt kann für die Client-zu-Akteur und jede Akteur-Akteur-Kommunikation verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ActorProxy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ActorProxy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> Proxy-Objekt zugeordnet.
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />die Proxy-Objekt zugeordnet ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClient As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClient : Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClient" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClient</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> -Schnittstelle, die diesen Proxy für die Kommunikation mit dem Akteur verwendet wird.
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />mit diesen Proxy für die Kommunikation mit dem Akteur.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClientV2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClientV2 As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClientV2 : Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.ActorServicePartitionClientV2" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClientV2</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> -Schnittstelle, die diesen Proxy für die Kommunikation mit dem Akteur verwendet wird.
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />mit diesen Proxy für die Kommunikation mit dem Akteur.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, Uri serviceUri, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Uri serviceUri, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.Uri,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * Uri * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, serviceUri, listenerName)" />
      <MemberType>Method</MemberType>
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
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="listenerName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TActorInterface">
            Der Akteur-Schnittstelle, die vom Objekt remote Akteur implementiert. Das zurückgegebene Proxyobjekt wird diese Schnittstelle implementieren.
            </typeparam>
        <param name="actorId">Akteur-Id des Objekts Akteur Proxy. Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser Id gesendet wird.</param>
        <param name="serviceUri">Der URI des Diensts Akteur.</param>
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
    <Member MemberName="Create&lt;TActorInterface&gt;">
      <MemberSignature Language="C#" Value="public static TActorInterface Create&lt;TActorInterface&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName = null, string serviceName = null, string listenerName = null) where TActorInterface : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TActorInterface Create&lt;(class Microsoft.ServiceFabric.Actors.IActor) TActorInterface&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string applicationName, string serviceName, string listenerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.ServiceFabric.Actors.ActorId * string * string * string -&gt; 'ActorInterface (requires 'ActorInterface :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.Client.ActorProxy.Create (actorId, applicationName, serviceName, listenerName)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId">Die Akteur-ID des Objekts Akteur Proxy. Methoden, die für diesen Proxy aufgerufen führt zu Anfragen an der Akteur mit dieser ID gesendet werden</param>
        <param name="applicationName">
            Der Name der Service Fabric-Anwendung, die der Akteur-Dienst hostet die Akteur-Objekte enthält.
            Dieser Parameter kann null sein, wenn der Client als Teil der gleichen Service Fabric-Anwendung ausgeführt wird. Weitere Informationen finden Sie in den Hinweisen. 
            </param>
        <param name="serviceName">
            Der Name des Service Fabric-Dienstes, je nach Konfiguration durch <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> auf die Akteur-Implementierung.
            Standardmäßig ist der Name des Diensts nicht mit dem Namen der Akteur-Schnittstelle abgeleitet. Allerdings <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> ist erforderlich, wenn ein Akteur mehr als ein Akteur Schnittstelle implementiert wird oder eine Akteur-Schnittstelle von einer anderen Akteur-Schnittstelle abgeleitet wird, da der Dienstname automatisch ermittelt werden kann.
            </param>
        <param name="listenerName">
            Standardmäßig verfügt ein Akteur-Dienst nur einen Listener für eine Verbindung herstellen und Kommunikation mit Clients.
            Allerdings ist es möglich, mehrere Listener einen Akteur-Dienst konfigurieren. Dieser Parameter gibt den Namen des Listeners für die Verbindung.
            </param>
        <summary>
            Erstellt einen Proxy für die Akteur-Objekt, das eine Akteur-Schnittstelle implementiert.
            </summary>
        <returns>Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</returns>
        <remarks>
          <para>Der Parameter "ApplicationName" ist null, wenn der Client als Teil der gleichen Service Fabric-Anwendung als Akteur-Dienst ausgeführt wird, für die Kommunikation mit beibehält. In diesem Fall wird der Anwendungsname aus bestimmt <see cref="T:System.Fabric.CodePackageActivationContext" />, und erfolgt durch Aufrufen über die <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" /> Eigenschaft.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>