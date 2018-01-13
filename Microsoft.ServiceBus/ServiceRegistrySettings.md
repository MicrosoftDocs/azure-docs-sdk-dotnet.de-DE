<Type Name="ServiceRegistrySettings" FullName="Microsoft.ServiceBus.ServiceRegistrySettings">
  <TypeSignature Language="C#" Value="public class ServiceRegistrySettings : System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRegistrySettings extends System.Object implements class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceRegistrySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRegistrySettings&#xA;Implements IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type ServiceRegistrySettings = class&#xA;    interface IEndpointBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IEndpointBehavior</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Enthält die Einstellungen für die Azure Service Bus-Registrierung.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettings (Microsoft.ServiceBus.DiscoveryType discoveryType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.DiscoveryType discoveryType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.#ctor(Microsoft.ServiceBus.DiscoveryType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServiceRegistrySettings : Microsoft.ServiceBus.DiscoveryType -&gt; Microsoft.ServiceBus.ServiceRegistrySettings" Usage="new Microsoft.ServiceBus.ServiceRegistrySettings discoveryType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="discoveryType" Type="Microsoft.ServiceBus.DiscoveryType" />
      </Parameters>
      <Docs>
        <param name="discoveryType">Der Discovery-Typ, der angibt, ob der Endpunkt öffentlich oder privat ist. </param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" /> -Klasse unter Verwendung der angegebenen Ermittlungstyp.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="allowUnauthenticatedAccess">
      <MemberSignature Language="C#" Value="protected bool allowUnauthenticatedAccess;" />
      <MemberSignature Language="ILAsm" Value=".field family bool allowUnauthenticatedAccess" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceRegistrySettings.allowUnauthenticatedAccess" />
      <MemberSignature Language="VB.NET" Value="Protected allowUnauthenticatedAccess As Boolean " />
      <MemberSignature Language="F#" Value="val mutable allowUnauthenticatedAccess : bool" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.allowUnauthenticatedAccess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>"true", wenn der Endpunkt für nicht authentifizierte Zugriffe zulässt; andernfalls "false". Der Standardwert ist „false“.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiscoveryMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.DiscoveryType DiscoveryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.DiscoveryType DiscoveryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceRegistrySettings.DiscoveryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DiscoveryMode As DiscoveryType" />
      <MemberSignature Language="F#" Value="member this.DiscoveryMode : Microsoft.ServiceBus.DiscoveryType with get, set" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.DiscoveryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.DiscoveryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, wie der Dienst ermittelt werden kann. </summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.DiscoveryType" />. DiscoveryType.Public für die Ermittlung öffentlich sein; DiscoveryType.Private für die Ermittlung auf privat sein. Der Standardwert ist DiscoveryType.Private.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceRegistrySettings.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Anzeigenamen für den Endpunkt.</summary>
        <value>Gibt <see cref="T:System.String" />. Enthält den Anzeigenamen an. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="bindingParameters" Type="System.ServiceModel.Channels.BindingParameterCollection" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der zu verändernde Endpunkt.</param>
        <param name="bindingParameters">Die Objekte, die von Bindungselementen zur Unterstützung des Verhaltens benötigt werden.</param>
        <summary>
            Übergibt Daten zur Laufzeit an Bindungen benutzerdefiniertes Verhalten unterstützen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="clientRuntime" Type="System.ServiceModel.Dispatcher.ClientRuntime" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt, der angepasst werden soll.</param>
        <param name="clientRuntime">Die Clientlaufzeit, die angepasst werden soll.</param>
        <summary>
            Diese Implementierung wird keine Aktion ausgeführt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyDispatchBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="endpointDispatcher" Type="System.ServiceModel.Dispatcher.EndpointDispatcher" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt, der angepasst werden soll.</param>
        <param name="endpointDispatcher">Der Endpunktverteiler, der geändert oder erweitert werden soll.</param>
        <summary>
            Diese Implementierung wird keine Aktion ausgeführt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.Validate">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.Validate (System.ServiceModel.Description.ServiceEndpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.Validate(class System.ServiceModel.Description.ServiceEndpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
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
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt dieses Verhalten gilt.</param>
        <summary>
            Diese Methode hat keine Funktion.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="transportProtectionEnabled">
      <MemberSignature Language="C#" Value="protected bool transportProtectionEnabled;" />
      <MemberSignature Language="ILAsm" Value=".field family bool transportProtectionEnabled" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceRegistrySettings.transportProtectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected transportProtectionEnabled As Boolean " />
      <MemberSignature Language="F#" Value="val mutable transportProtectionEnabled : bool" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.transportProtectionEnabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>"true", wenn der transportschutz aktiviert ist; andernfalls "false". Der Standardwert lautet „true“.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>