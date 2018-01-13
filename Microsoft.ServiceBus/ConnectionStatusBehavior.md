<Type Name="ConnectionStatusBehavior" FullName="Microsoft.ServiceBus.ConnectionStatusBehavior">
  <TypeSignature Language="C#" Value="public class ConnectionStatusBehavior : Microsoft.ServiceBus.IConnectionStatus, System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionStatusBehavior extends System.Object implements class Microsoft.ServiceBus.IConnectionStatus, class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectionStatusBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionStatusBehavior&#xA;Implements IConnectionStatus, IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type ConnectionStatusBehavior = class&#xA;    interface IEndpointBehavior&#xA;    interface IConnectionStatus" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceBus.IConnectionStatus</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IEndpointBehavior</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Ein Endpunktverhalten, das Zugriff auf den Verbindungsstatus von einem Dienst überwacht Azure Service Bus bietet.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionStatusBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ConnectionStatusBehavior" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connecting">
      <MemberSignature Language="C#" Value="public event EventHandler Connecting;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Connecting" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.ConnectionStatusBehavior.Connecting" />
      <MemberSignature Language="VB.NET" Value="Public Event Connecting As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Connecting : EventHandler " Usage="member this.Connecting : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceBus.IConnectionStatus.Connecting</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Endpunkt des Relay-Diensts und bei jedem erneuten Versuch vorübergehend getrennt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOnline">
      <MemberSignature Language="C#" Value="public bool IsOnline { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOnline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ConnectionStatusBehavior.IsOnline" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOnline As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOnline : bool" Usage="Microsoft.ServiceBus.ConnectionStatusBehavior.IsOnline" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.IConnectionStatus.IsOnline</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der bestimmt, ob die Verbindung online ist.</summary>
        <value>"true", wenn die Verbindung online ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastError">
      <MemberSignature Language="C#" Value="public Exception LastError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception LastError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ConnectionStatusBehavior.LastError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastError As Exception" />
      <MemberSignature Language="F#" Value="member this.LastError : Exception" Usage="Microsoft.ServiceBus.ConnectionStatusBehavior.LastError" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.IConnectionStatus.LastError</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den letzten Fehler ab.</summary>
        <value>Gibt eine <see cref="T:System.Exception" /> , die den letzten Fehler enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="public event EventHandler Offline;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Offline" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.ConnectionStatusBehavior.Offline" />
      <MemberSignature Language="VB.NET" Value="Public Event Offline As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Offline : EventHandler " Usage="member this.Offline : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceBus.IConnectionStatus.Offline</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Endpunkt beendet wird, eine Verbindung mit dem Relaydienst herzustellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Online">
      <MemberSignature Language="C#" Value="public event EventHandler Online;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Online" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.ConnectionStatusBehavior.Online" />
      <MemberSignature Language="VB.NET" Value="Public Event Online As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Online : EventHandler " Usage="member this.Online : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceBus.IConnectionStatus.Online</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Endpunkt wurde erfolgreich an den Relaydienst stellt eine Verbindung her.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="public void Retry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Retry() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.Retry" />
      <MemberSignature Language="VB.NET" Value="Public Sub Retry ()" />
      <MemberSignature Language="F#" Value="member this.Retry : unit -&gt; unit" Usage="connectionStatusBehavior.Retry " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Versucht, die Verbindung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
      <MemberSignature Language="VB.NET" Value="Sub AddBindingParameters (endpoint As ServiceEndpoint, bindingParameters As BindingParameterCollection) Implements IEndpointBehavior.AddBindingParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="bindingParameters" Type="System.ServiceModel.Channels.BindingParameterCollection" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der zu verändernde Endpunkt.</param>
        <param name="bindingParameters">Die Objekte, die von Bindungselementen zur Unterstützung des Verhaltens benötigt werden.</param>
        <summary>
            Übergibt Daten zur Laufzeit an Bindungen benutzerdefiniertes Verhalten unterstützen. Diese Implementierung wird keine Aktion ausgeführt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="behavior" Type="System.ServiceModel.Dispatcher.ClientRuntime" />
      </Parameters>
      <Docs>
        <param name="serviceEndpoint">Der Endpunkt, der angepasst werden soll.</param>
        <param name="clientRuntime">Die Clientlaufzeit, die angepasst werden soll.</param>
        <summary>
            Diese Implementierung wird keine Aktion ausgeführt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyDispatchBehavior (System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(class System.ServiceModel.Description.ServiceEndpoint serviceEndpoint, class System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="endpointDispatcher" Type="System.ServiceModel.Dispatcher.EndpointDispatcher" />
      </Parameters>
      <Docs>
        <param name="serviceEndpoint">Der Endpunkt, der angepasst werden soll.</param>
        <param name="endpointDispatcher">Der Endpunktverteiler, der geändert oder erweitert werden soll.</param>
        <summary>
            Der Listener Runtime Verbindungsereignisse Status verknüpft.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.Validate">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.Validate (System.ServiceModel.Description.ServiceEndpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.Validate(class System.ServiceModel.Description.ServiceEndpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectionStatusBehavior.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
      <MemberSignature Language="VB.NET" Value="Sub Validate (endpoint As ServiceEndpoint) Implements IEndpointBehavior.Validate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.Validate(System.ServiceModel.Description.ServiceEndpoint)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceEndpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt dieses Verhalten gilt.</param>
        <summary>
            Diese Methode hat keine Funktion.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>