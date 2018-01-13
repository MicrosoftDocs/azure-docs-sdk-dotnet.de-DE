<Type Name="FabricTransportServiceRemotingProviderAttribute" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingProviderAttribute : Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingProviderAttribute extends Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingProviderAttribute&#xA;Inherits ServiceRemotingProviderAttribute" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingProviderAttribute = class&#xA;    inherit ServiceRemotingProviderAttribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.ServiceRemotingProviderAttribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             Legt den Fabric-TCP-Transport als Standard-Remoting Transport Dienstanbieter in der Assembly fest.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingProviderAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute" /> die festzulegende Fabric-TCP-Transport als Standard-Remoting Transport Dienstanbieter in der Assembly verwendet werden können.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public long ConnectTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeoutInMilliseconds As Long" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeoutInMilliseconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.ConnectTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory(Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactory (callbackClient As IServiceRemotingCallbackClient) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactory : Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactory callbackClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
                Erstellt eine Factory V1 Dienst Remoting Client zum Herstellen einer Verbindung mit dem Dienst über Remote Dienstschnittstellen.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> Dienstproxy zu wenden Sie sich an einen Dienst zustandslose oder zustandsbehaftete über Remote Akteur-Schnittstelle generiert.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingClientFactoryV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2 (Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory CreateServiceRemotingClientFactoryV2(class Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler callbackMessageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2(Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateServiceRemotingClientFactoryV2 (callbackMessageHandler As IServiceRemotingCallbackMessageHandler) As IServiceRemotingClientFactory" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingClientFactoryV2 : Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingClientFactoryV2 callbackMessageHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingCallbackMessageHandler" />
      </Parameters>
      <Docs>
        <param name="callbackMessageHandler">
               Die Clientimplementierung, in denen die Rückrufe weitergeleitet werden soll.
            </param>
        <summary>
                Erstellt eine Factory V2 Dienst Remoting Client zum Herstellen einer Verbindung mit dem Dienst über Remote Dienstschnittstellen.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Client.IServiceRemotingClientFactory" /> , die verwendet werden kann, mit <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceProxyFactory" /> Dienstproxy zu wenden Sie sich an einen Dienst zustandslose oder zustandsbehaftete über Remote Akteur-Schnittstelle generiert.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt für die Implementierung.
            </param>
        <summary>
                Erstellt einen Dienst Remoting-Listener für das Remoting Dienstschnittstelle an.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für die angegebene dienstimplementierung.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListenerV2">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2 (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListenerV2(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceRemotingListenerV2 : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" Usage="fabricTransportServiceRemotingProviderAttribute.CreateServiceRemotingListenerV2 (serviceContext, serviceImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt für die Implementierung.
            </param>
        <summary>
                Erstellt einen V2 Dienst Remoting-Listener für das Remoting Dienstschnittstelle.
            </summary>
        <returns>
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" /> als <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für die angegebene dienstimplementierung.
                </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long KeepAliveTimeoutInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.KeepAliveTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInSeconds : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportServiceRemotingProviderAttribute.OperationTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft ab oder legt die Zeitüberschreitung in Sekunden fest. Wenn der Vorgang nicht in der angegebenen Zeit abgeschlossen ist, wird es Zeitlimit überschritten werden. Standardmäßig wird der Ausnahmehandler <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Client.FabricTransportServiceRemotingClientFactory" /> wiederholt die zeitgesteuerte out Ausnahme. Es wird nicht ändern Timeout für den Vorgang aus den Standardwert empfohlen. 
                </summary>
        <value>
                Timeout für den Vorgang in Sekunden. Wenn nicht angegebenen oder kleiner als 0 (null), Standardvorgang Timeout der maximale Wert wird verwendet. 
                </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>