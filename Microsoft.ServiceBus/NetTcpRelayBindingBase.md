<Type Name="NetTcpRelayBindingBase" FullName="Microsoft.ServiceBus.NetTcpRelayBindingBase">
  <TypeSignature Language="C#" Value="public abstract class NetTcpRelayBindingBase : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NetTcpRelayBindingBase extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NetTcpRelayBindingBase&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBindingBase = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.Binding</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Die Basisklasse für allgemeine Methoden für die <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> Bindung.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBindingBase : string -&gt; Microsoft.ServiceBus.NetTcpRelayBindingBase" Usage="new Microsoft.ServiceBus.NetTcpRelayBindingBase configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName">Der Konfigurationsname der Bindung.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> -Klasse mit dem angegebenen Konfigurationsnamen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBindingBase : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.NetTcpRelayBindingBase" Usage="new Microsoft.ServiceBus.NetTcpRelayBindingBase (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode">Mit der Bindung verwendeten Sicherheitstyp.</param>
        <param name="relayClientAuthenticationType">Der Typ des Relayauthentifizierung verwendet.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> Klasse, mit dem angegebenen Modus und Relay-Authentifizierungstyp.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, Microsoft.ServiceBus.NetTcpRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class Microsoft.ServiceBus.NetTcpRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,Microsoft.ServiceBus.NetTcpRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, security As NetTcpRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBindingBase : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * Microsoft.ServiceBus.NetTcpRelaySecurity -&gt; Microsoft.ServiceBus.NetTcpRelayBindingBase" Usage="new Microsoft.ServiceBus.NetTcpRelayBindingBase (transport, encoding, security)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetTcpRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="transport"> Der Transport.</param>
        <param name="encoding"> Die Codierung.</param>
        <param name="security"> Die Sicherheit.</param>
        <summary>Initialisiert eine neue Instanz der dem<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> -Klasse unter Verwendung der angegebenen Transport, Codierung und Sicherheit.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected virtual void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="abstract member ApplyConfiguration : string -&gt; unit&#xA;override this.ApplyConfiguration : string -&gt; unit" Usage="netTcpRelayBindingBase.ApplyConfiguration configurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName">Der Name des Konfigurationselements werden die Einstellungen aus.</param>
        <summary>Die Einstellungen des Konfigurationselements, das entspricht dem angegebenen Namen auf die aktuelle Instanz dieses Bindungselements angewendet.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException">Das Bindungselement, das die Eingabekonfiguration namentlich in der Konfiguration angegebene wurde nicht gefunden werden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Verbindungsmodus: <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" /> oder <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> , die die Verbindung enthält Modus; entweder <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" /> oder <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />. Die Standardeinstellung ist mittels Relay weitergeleitet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netTcpRelayBindingBase.CreateBindingElements " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElementCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine geordnete Auflistung von Bindungselementen, die in der aktuellen Bindung enthalten sind.</summary>
        <returns>Gibt eine <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> , aus die Bindung besteht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected internal abstract System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="netTcpRelayBindingBase.CreateMessageSecurity " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.SecurityBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt das Sicherheitsbindungselement, das für die aktuelle Instanz.</summary>
        <returns>Gibt eine <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> , enthält das Sicherheitsbindungselement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="encoding">
      <MemberSignature Language="C#" Value="protected internal System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding;" />
      <MemberSignature Language="ILAsm" Value=".field familyorassembly class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NetTcpRelayBindingBase.encoding" />
      <MemberSignature Language="VB.NET" Value="Protected Friend encoding As BinaryMessageEncodingBindingElement " />
      <MemberSignature Language="F#" Value="val mutable encoding : System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.encoding" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BinaryMessageEncodingBindingElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Das Attribut Codierung-Elements für die aktuelle Instanz. Sowie die Einstellungen für Sicherheit und Transport bildet die Codierung die drei wichtigsten Eigenschaften einer Bindung aus.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die SOAP-Version ab, die für Nachrichten verwendet wird, die von dieser Bindung verarbeitet werden.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.EnvelopeVersion" /> , enthält die Umschlagversion für diese Bindung verwendet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen des verwendet auf den Hostnamen-Vergleichsmodus.</summary>
        <value>Der Vergleichsmodus auf den Hostnamen verwendet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBindingElementsMatch">
      <MemberSignature Language="C#" Value="protected bool IsBindingElementsMatch (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsBindingElementsMatch(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.IsBindingElementsMatch(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsBindingElementsMatch (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBindingElementsMatch : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement -&gt; bool" Usage="netTcpRelayBindingBase.IsBindingElementsMatch (transport, encoding)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
      </Parameters>
      <Docs>
        <param name="transport"> Das Transportbindungselement erfolgen.</param>
        <param name="encoding"> Dem Codierungsbindungselement.</param>
        <summary>Bestimmt, ob die angegebenen Bindungselemente, die Standardwerte für die Bindungselemente in der aktuellen Instanz übereinstimmen.</summary>
        <returns>"true", wenn die Elemente übereinstimmen; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob die RelayBindung dynamisch ist.</summary>
        <value>"true", wenn die RelayBindung dynamisch ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange ab, oder legt diese fest.</summary>
        <value>Gibt die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange zurück. Der Standard ist 10.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale zulässige Größe für einen Pufferpool, der speichert Sie Nachrichten, die von der Bindung verarbeitet werden.</summary>
        <value>Gibt die maximale Größe in Bytes, der für einen Pufferpool, der von der Bindung verarbeitete Nachrichten speichert zulässig. Der Standardwert ist 65.536.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der die maximale Größe des Puffers zum Speichern von Nachrichten im Arbeitsspeicher angibt.</summary>
        <value>Gibt die maximale Größe des Puffers zum Speichern von Nachrichten im Arbeitsspeicher in Bytes zurück. Der Standardwert ist 65.536.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab, der die maximale Anzahl an Verbindungen, die für die nachfolgende Wiederverwendung auf dem Client gepoolt werden sollen, und die maximale Anzahl an Verbindungen steuert, für die eine ausstehende Übermittlung auf dem Server zulässig ist.</summary>
        <value>Auf dem Client gibt die maximale Anzahl an Verbindungen, für die nachfolgende Wiederverwendung "zusammengelegt" werden; auf dem Server gibt Sie die maximale Anzahl zulässiger Verbindungen mit "Ausstehend" Verteilung zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Größe für eine empfangene Nachricht ab, die von der Bindung verarbeitet wird, oder legt sie fest.</summary>
        <value>Gibt die maximale Größe in Byte für eine empfangene Nachricht, die von der Bindung verarbeitet wird. Der Standardwert ist 65.536.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageSecurityVersion">
      <MemberSignature Language="C#" Value="protected internal System.ServiceModel.MessageSecurityVersion MessageSecurityVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.MessageSecurityVersion MessageSecurityVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MessageSecurityVersion" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property MessageSecurityVersion As MessageSecurityVersion" />
      <MemberSignature Language="F#" Value="member this.MessageSecurityVersion : System.ServiceModel.MessageSecurityVersion" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MessageSecurityVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageSecurityVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die nachrichtensicherheitsversion ab.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.MessageSecurityVersion" /> , enthält die nachrichtensicherheitsversion. Dies zurzeit immer zurück, MessageSecurityVersion..::. WSSecurity11WSTrustFebruary2005WSSecureConversationFebruary2005WSSecurityPolicy11. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft Beschränkungen der Komplexität von SOAP-Meldungen ab, die von Endpunkten verarbeitet werden können, die mit dieser Bindung konfiguriert werden, oder legt die Beschränkungen fest. Diese Eigenschaft darf nicht null sein.</summary>
        <value>Gibt eine <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> , das die komplexitätseinschränkungen für ausgetauschte SOAP-Nachrichten angibt. Die Standardwerte für diese Einschränkungen werden im folgenden Hinweisabschnitt angegeben.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> Wenn ReaderQuotas null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das URI-Schema für den Transport ab.</summary>
        <value>Gibt das URI-Schema für die Übertragung zurück. Der Standardwert ist "Sb".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NetTcpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NetTcpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetTcpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.NetTcpRelaySecurity" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NetTcpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ein Objekt ab, das den Sicherheitstyp angibt, der mit den mit dieser Bindung konfigurierten Diensten verwendet wird.</summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />, die mit dieser Bindung verwendeten Sicherheitstypen enthält. Der Modus der Sicherheit ist Transport.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass eingehende Anforderungen asynchron gehandhabt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab, der angibt, ob der mit der Bindung konfigurierte Dienst den Streaming- oder Puffermodus (oder beides) für die Nachrichtenübertragung einsetzt oder legt diesen Wert fest.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> , der angibt, ob der Dienst mit der Bindung verwendet Streaming- oder Puffermodus (oder beides) konfiguriert nachrichtenübertragung. Standardmäßig verwenden HTTP, TCP/IP sowie named Pipe-Transporte gepufferte nachrichtenübertragungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="transport">
      <MemberSignature Language="C#" Value="protected internal Microsoft.ServiceBus.TcpRelayTransportBindingElement transport;" />
      <MemberSignature Language="ILAsm" Value=".field familyorassembly class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NetTcpRelayBindingBase.transport" />
      <MemberSignature Language="VB.NET" Value="Protected Friend transport As TcpRelayTransportBindingElement " />
      <MemberSignature Language="F#" Value="val mutable transport : Microsoft.ServiceBus.TcpRelayTransportBindingElement" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayTransportBindingElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Das Transportelement für die aktuelle Instanz. Zusammen mit der Codierung und Sicherheit bildet der transporteinstellung die Kerneigenschaften des eine Bindung an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>