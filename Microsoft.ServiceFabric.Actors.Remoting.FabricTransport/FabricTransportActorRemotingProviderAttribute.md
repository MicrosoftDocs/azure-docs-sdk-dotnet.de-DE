<Type Name="FabricTransportActorRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public class FabricTransportActorRemotingProviderAttribute : Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportActorRemotingProviderAttribute extends Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportActorRemotingProviderAttribute&#xA;Inherits ActorRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type FabricTransportActorRemotingProviderAttribute = class&#xA;    inherit ActorRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Actors.Remoting.ActorRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Assembly)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
                Legt den TCP-Transport Fabric als Standardanbieter Remoting für die Akteure fest.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportActorRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute" />, die festzulegende Fabric TCP-Transport als Standardanbieter Remoting für die Akteure verwendet werden können.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public long ConnectTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeoutInMilliseconds As Long" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeoutInMilliseconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt die Connect Timeout in Millisekunden. Diese Einstellung gibt die maximale Zeitspanne für die Verbindung eingerichtet werden kann.
                </summary>
        <value>
                Das Connect Timeout in Millisekunden.
            </value>
        <remarks>Standardwert für ConnectTimeout-Timeout beträgt 5 Sekunden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactory">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory (Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactory(class Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient callbackClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackClient" Type="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
      </Parameters>
      <Docs>
        <param name="callbackClient">
                Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.
            </param>
        <summary>
                Erstellt eine Factory Dienst Remoting Client, für die Verbindung zu den Remote Akteur-Schnittstellen.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Client.FabricTransportActorRemotingClientFactory" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.ActorProxyFactory" /> um Akteur Proxy mit dem Akteur über Remote Akteur Schnittstelle sprechen zu generieren.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListener(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListener actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                Die Implementierung der Akteur-Dienst, der die Akteure hostet, deren Schnittstellen Remote ausgeführt werden muss.
                </param>
        <summary>
                Erstellt einen Dienst Remoting-Listener für das Remoting die Akteur-Schnittstellen.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Akteur-Dienst.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListenerV2(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportActorRemotingProviderAttribute.CreateServiceRemotingListenerV2 actorService" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">
                Die Implementierung der Akteur-Dienst, der die Akteure hostet, deren Schnittstellen Remote ausgeführt werden muss.
                </param>
        <summary>
                Erstellt einen Dienst Remoting-Listener für das Remoting die Akteur-Schnittstellen.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.FabricTransport.Runtime.FabricTransportActorServiceRemotingListener" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für den angegebenen Akteur-Dienst.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long KeepAliveTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt das Keep-alive-Timeout in Sekunden fest. Diese Einstellung ist hilfreich, wenn Client und Dienst über Lastenausgleich verbunden sind, die die Verbindung geschlossen wird, wenn es einige Zeit im Leerlauf befunden hat.
                Wenn Keep-alive-Timeout konfiguriert ist, die Verbindung aktiv bleiben per Ping-Nachrichten in diesem Intervall.
                </summary>
        <value>
                Die Keep-alive-Timeout in Sekunden.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Größe der Remoting-Nachricht in Bytes fest.
            Wenn kein Wert für diese Eigenschaft angegeben wird, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.
            </summary>
        <value>
                Die maximale Größe der Remoting Nachricht in Bytes. Wenn dieser Wert nicht angegeben ist, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long OperationTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OperationTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.FabricTransport.FabricTransportActorRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt die Zeitüberschreitung in Sekunden fest. Wenn der Vorgang nicht in der angegebenen Zeit abgeschlossen ist, wird es Zeitlimit überschritten werden. Standardmäßig Ausnahmehandler des FabricTransportServiceRemotingClientFactory /&gt; wiederholt die zeitgesteuerte out Ausnahme. Es wird nicht ändern Timeout für den Vorgang aus den Standardwert empfohlen. 
                </summary>
        <value>
                Timeout für den Vorgang in Sekunden. Wenn nicht angegebenen oder kleiner als 0 (null), Standardvorgang Timeout der maximale Wert wird verwendet. 
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>