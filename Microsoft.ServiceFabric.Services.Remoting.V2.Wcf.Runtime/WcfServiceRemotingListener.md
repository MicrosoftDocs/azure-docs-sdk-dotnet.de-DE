<Type Name="WcfServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> , verwendet Windows Communication Foundation Schnittstelle Remoting für Zustandslose und zustandsbehaftete Dienste bereitzustellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, System.ServiceModel.Channels.Binding listenerBinding = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, string endpointResourceName = &quot;ServiceEndpointV2&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class System.ServiceModel.Channels.Binding listenerBinding, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, serviceImplementation, listenerBinding, serializationProvider, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</param>
        <param name="serviceImplementation">Das Dienstobjekt für die Implementierung.</param>
        <param name="listenerBinding">WCF-Bindung für den Listener verwendet. Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode erstellt eine <see cref="T:System.ServiceModel.NetTcpBinding" /> ohne Sicherheit.
            </param>
        <param name="serializationProvider"></param>
        <param name="endpointResourceName">Der Name der endpunktressource definiert, in das Manifest, das verwendet werden soll, um die Adresse für den Listener zu erstellen. Wenn die EndpointResourceName nicht angegebenen oder null ist, ist der Standardwert "ServiceEndpointV2" verwendet.
            </param>
        <summary>
            Ein WCF-Konstrukte basierend Dienst Remoting Listener. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, serializationProvider, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</param>
        <param name="messageHandler">Der Handler für das empfangen und Verarbeiten von Nachrichten von Remoting. Beim Empfangen von Nachrichten übermittelt der Listener die Nachrichten an den Handler.
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding">WCF-Bindung für den Listener verwendet. Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode.
            </param>
        <param name="address">Die Endpunktadresse für den WCF-Listener verwendet werden soll. Wenn dies nicht der angegebenen "oder" null ", die Endpunktadresse wird erstellt unter Verwendung der Standard-Endpunkt-Ressource mit dem Namen"ServiceEndpointV2"in das Manifest definiert. 
            </param>
        <summary>
            Ein WCF-Konstrukte basierend Dienst Remoting Listener. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = &quot;ServiceEndpointV2&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, serializationProvider, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Der Kontext des Diensts für das Remoting-Listener erstellt wird.</param>
        <param name="messageHandler">Der Handler für das empfangen und Verarbeiten von Nachrichten von Remoting. Beim Empfangen von Nachrichten übermittelt der Listener die Nachrichten an den Handler.
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding">WCF-Bindung für den Listener verwendet. Wenn der Listener, der Bindung nicht angegeben ist oder null, ein Standardlistener, die Bindung wird mithilfe der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> Methode erstellt eine <see cref="T:System.ServiceModel.NetTcpBinding" /> ohne Sicherheit.
            </param>
        <param name="endpointResourceName">Der Name der endpunktressource definiert, in das Manifest, das verwendet werden soll, um die Adresse für den Listener zu erstellen. Wenn die EndpointResourceName nicht angegeben ist, oder es null ist, ist der Standardwert "ServiceEndpointV2" verwendet.
            </param>
        <summary>
            Ein WCF-Konstrukte basierend Dienst Remoting Listener. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Diese Methode bewirkt, dass den Listener Kommunikation zu schließen. Schließen ist ein Endstatus und diese Methode bewirkt, dass des Übergangs nicht ordnungsgemäß geschlossen. Alle ausstehenden Vorgänge (einschließlich schließen) sollte abgebrochen werden, wenn diese Methode aufgerufen wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese Methode bewirkt, dass den Listener Kommunikation zu schließen. Schließen ist ein Endstatus und diese Methode ermöglicht die Kommunikation-Listener für den Übergang in diesen Zustand auf ordnungsgemäße Weise.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Diese Methode bewirkt, dass die Kommunikation Listener geöffnet werden. Nach Abschluss der öffnen, der Listener für die Kommunikation wird verwendbar - akzeptiert, und sendet Nachrichten ab.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis der Aufgabe ist die Endpunktzeichenfolge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                Ruft die <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.
                </summary>
        <value>
                Ein <see cref="T:System.ServiceModel.ServiceHost" /> , die zum Hosten von WCF-Dienst-Implementierung von diesem Listener verwendet.
                </value>
        <remarks>
                Der Diensthost wird vom Listener in seinem Konstruktor erstellt. Bevor Sie diese Kommunikation Listener geöffnet wird, von der Laufzeit über <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> -Methode, der Diensthost durch den Zugriff auf ihn über diese Eigenschaft angepasst werden.
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>