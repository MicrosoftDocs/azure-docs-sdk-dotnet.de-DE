<Type Name="NetTcpRelayBinding" FullName="Microsoft.ServiceBus.NetTcpRelayBinding">
  <TypeSignature Language="C#" Value="public class NetTcpRelayBinding : Microsoft.ServiceBus.NetTcpRelayBindingBase, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetTcpRelayBinding extends Microsoft.ServiceBus.NetTcpRelayBindingBase implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class NetTcpRelayBinding&#xA;Inherits NetTcpRelayBindingBase&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBinding = class&#xA;    inherit NetTcpRelayBindingBase&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.NetTcpRelayBindingBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Bietet eine sichere, zuverlässige Bindung, die für die computerübergreifende Kommunikation geeignet ist.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : string -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName">Die zu verwendende Konfiguration.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> Klasse mit einer angegebenen XML-Konfiguration. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding (securityMode, relayClientAuthenticationType)" />
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
        <param name="securityMode">Mit der Bindung verwendeten Sicherheitstyp. </param>
        <param name="relayClientAuthenticationType">Der Typ der Clientauthentifizierung auf das Relay verwendet werden soll. </param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> -Klasse mit den verwendeten Sicherheitstyp und relay-Clientauthentifizierung angegeben. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType * bool -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding (securityMode, relayClientAuthenticationType, reliableSessionEnabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
        <Parameter Name="reliableSessionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="securityMode">Der Typ der Sicherheit, die mit der Azure Service Bus-Bindung verwendet.</param>
        <param name="relayClientAuthenticationType">Der Typ der Clientauthentifizierung auf das Relay verwendet werden soll. </param>
        <param name="reliableSessionEnabled">"true", wenn zuverlässige Sitzungen aktiviert sind; andernfalls "false".</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> -Klasse mit den Typ der Sicherheit verwendet, den Typ der Clientauthentifizierung und ein Wert, der angibt, ob zuverlässige Sitzungen explizit aktiviert werden.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBinding (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, System.ServiceModel.Channels.ReliableSessionBindingElement session, Microsoft.ServiceBus.NetTcpRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class System.ServiceModel.Channels.ReliableSessionBindingElement session, class Microsoft.ServiceBus.NetTcpRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,System.ServiceModel.Channels.ReliableSessionBindingElement,Microsoft.ServiceBus.NetTcpRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, session As ReliableSessionBindingElement, security As NetTcpRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * System.ServiceModel.Channels.ReliableSessionBindingElement * Microsoft.ServiceBus.NetTcpRelaySecurity -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding (transport, encoding, session, security)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="session" Type="System.ServiceModel.Channels.ReliableSessionBindingElement" />
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetTcpRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="transport">Das Transportbindungselement zu verwenden.</param>
        <param name="encoding">Die zu verwendende Codierung.</param>
        <param name="session">Das Bindungselement der zuverlässigen Sitzung.</param>
        <param name="security">Das Sicherheitsbindungselement.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> -Klasse mit angegebenen Transport, Encoder, zuverlässiges sitzungsbindungselement und Typ der Sicherheit verwendet.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : string -&gt; unit" Usage="netTcpRelayBinding.ApplyConfiguration configurationName" />
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
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netTcpRelayBinding.CreateBindingElements " />
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
        <summary>Erstellt eine Auflistung mit den Bindungselementen für die Bindung. </summary>
        <returns>Gibt eine <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> , die den geordneten Stapel von Bindungselementen enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected internal override System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="netTcpRelayBinding.CreateMessageSecurity " />
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
        <summary>Erstellt die Meldung Sicherheitstoken für die aktuelle Instanz. </summary>
        <returns>Gibt <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />. Enthält das Sicherheitstoken für die Nachricht an. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBindingElementsMatch">
      <MemberSignature Language="C#" Value="protected bool IsBindingElementsMatch (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, System.ServiceModel.Channels.ReliableSessionBindingElement session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsBindingElementsMatch(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class System.ServiceModel.Channels.ReliableSessionBindingElement session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.IsBindingElementsMatch(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,System.ServiceModel.Channels.ReliableSessionBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsBindingElementsMatch (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, session As ReliableSessionBindingElement) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBindingElementsMatch : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * System.ServiceModel.Channels.ReliableSessionBindingElement -&gt; bool" Usage="netTcpRelayBinding.IsBindingElementsMatch (transport, encoding, session)" />
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
        <Parameter Name="session" Type="System.ServiceModel.Channels.ReliableSessionBindingElement" />
      </Parameters>
      <Docs>
        <param name="transport"> Vom Transport die Durchführung übereinstimmen. </param>
        <param name="encoding"> Die Codierung entsprechend. </param>
        <param name="session"> Die Sitzung überein. </param>
        <summary>Gibt einen Wert, der bestimmt, ob die angegebenen Objekte übereinstimmende Bindungselemente verfügen. </summary>
        <returns>Gibt<see cref="T:System.Boolean" />.True zurück, wenn die Objekte entsprechen; andernfalls, "false". </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.OptionalReliableSession ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.OptionalReliableSession ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBinding.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As OptionalReliableSession" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.OptionalReliableSession" Usage="Microsoft.ServiceBus.NetTcpRelayBinding.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.OptionalReliableSession</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ein Objekt, das angibt, ob eine zuverlässige Sitzung zwischen kanalendpunkten Azure Service Bus hergestellt wird. </summary>
        <value>Gibt <see cref="T:System.ServiceModel.OptionalReliableSession" />. Gibt an, ob eine zuverlässige WS-RM-Sitzung zwischen kanalendpunkten eingerichtet wird. Der Standardwert ist false.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>