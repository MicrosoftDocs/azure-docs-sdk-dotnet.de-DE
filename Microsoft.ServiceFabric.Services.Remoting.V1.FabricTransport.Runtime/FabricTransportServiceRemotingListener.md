<Type Name="FabricTransportServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />
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
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird. 
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt-Implementierung verwendet, um erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" /> für die Nachrichtenverarbeitung.
                </param>
        <summary>
                Erstellt einen Fabric transportbasierte Dienst Remoting-Listener mit dem Standardwert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="messageHandler">
                Der Handler für die Verarbeitung von Nachrichten von Remoting. Wie die Nachrichten empfangen werden, werden Sie von der Listener an diesen Handler übermittelt.
                </param>
        <summary>
                Erstellt einen Fabric transportbasierte Dienst Remoting-Listener mit dem Standardwert <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt-Implementierung verwendet, um erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" /> für die Nachrichtenverarbeitung.
                </param>
        <param name="listenerSettings">
                Die Einstellungen für den Listener.
            </param>
        <summary>
                Erstellt einen Fabric transportbasierte Dienst Remoting-Listener mit dem angegebenen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, string listenerSettingsConfigSectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, string listenerSettingsConfigSectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, listenerSettingsConfigSectionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerSettingsConfigSectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="serviceImplementation">
                Das Dienstobjekt-Implementierung verwendet, um erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" /> für die Nachrichtenverarbeitung.
                </param>
        <param name="listenerSettingsConfigSectionName">
               Der Name des Konfigurationsabschnitts in das Konfigurationspaket namens "Config" in das Manifest, das die Einstellungen für den Listener definiert. 
               </param>
        <summary>
                Erstellt einen Listener mit dem Fabric transportbasierte Dienst Remoting <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> im Abschnitt "Konfiguration" geladen.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="messageHandler">
                Der Handler für die Verarbeitung von Nachrichten von Remoting. Wie die Nachrichten empfangen werden, werden Sie von der Listener an diesen Handler übermittelt.
                </param>
        <param name="listenerSettings">
                Die Einstellungen für den Listener verwendet.
            </param>
        <summary>
                Erstellt einen Fabric transportbasierte Dienst Remoting-Listener mit dem angegebenen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, string listenerSettingsConfigSectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, string listenerSettingsConfigSectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler, listenerSettingsConfigSectionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettingsConfigSectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                Der Kontext des Diensts für das Remoting-Listener erstellt wird.
            </param>
        <param name="messageHandler">
                Der Handler für die Verarbeitung von Nachrichten von Remoting. Wie die Nachrichten empfangen werden, werden Sie von der Listener an diesen Handler übermittelt.
                </param>
        <param name="listenerSettingsConfigSectionName">
               Der Name des Konfigurationsabschnitts in das Konfigurationspaket namens "Config" in das Manifest, das die Einstellungen für den Listener definiert. 
               </param>
        <summary>
                Erstellt einen Listener mit dem Fabric transportbasierte Dienst Remoting <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> im Abschnitt "Konfiguration" geladen.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
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
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
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
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
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
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
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