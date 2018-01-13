<Type Name="FabricTransportServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
                Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> , Fabric TCP-Transport verwendet, Schnittstelle Remoting für Zustandslose und zustandsbehaftete Dienste bereitzustellen.
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, remotingListenerSettings, serializationProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="remotingListenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird. 
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt-Implementierung verwendet, um erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" /> für die Nachrichtenverarbeitung.
                </param>
        <param name="remotingListenerSettings">Die Einstellungen für den listener</param>
        <param name="serializationProvider">Dient zum Serialisieren Deserialisieren der Anforderung und den Antworttext </param>
        <summary>
                Erstellt einen Fabric transportbasierte Dienst Remoting-Listener an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler serviceRemotingMessageHandler, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceRemotingMessageHandler, remotingListenerSettings, serializationProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceRemotingMessageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="remotingListenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceRemotingMessageHandler">
                Der Handler für die Verarbeitung von Nachrichten von Remoting. Wie die Nachrichten empfangen werden, werden Sie von der Listener an diesen Handler übermittelt.
                </param>
        <param name="remotingListenerSettings">Die Einstellungen für den listener</param>
        <param name="serializationProvider">Dient zum Serialisieren Deserialisieren der Anforderung und den Antworttext </param>
        <summary>
                Erstellt einen Fabric transportbasierte Dienst Remoting-Listener an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit&#xA;override this.Abort : unit -&gt; unit" Usage="fabricTransportServiceRemotingListener.Abort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricTransportServiceRemotingListener.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener/&lt;CloseAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
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
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.FabricTransport.Runtime.FabricTransportServiceRemotingListener.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="fabricTransportServiceRemotingListener.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
  </Members>
</Type>