<Type Name="TcpRelayTransportBindingElement" FullName="Microsoft.ServiceBus.TcpRelayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class TcpRelayTransportBindingElement : Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement, System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TcpRelayTransportBindingElement extends Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement implements class System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TcpRelayTransportBindingElement&#xA;Inherits ConnectionOrientedTransportBindingElement&#xA;Implements IPolicyExportExtension" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportBindingElement = class&#xA;    inherit ConnectionOrientedTransportBindingElement&#xA;    interface IPolicyExportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Stellt das Bindungselement, das für das TCP-Transport-Relay dar. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" />-Klasse. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TcpRelayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.TcpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.TcpRelayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType">Die relayclient-Authentifizierungstyp.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" /> -Klasse unter Verwendung der angegebenen relayclient-Authentifizierungstyp. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TcpRelayTransportBindingElement (Microsoft.ServiceBus.TcpRelayTransportBindingElement elementToBeCloned);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TcpRelayTransportBindingElement elementToBeCloned) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.TcpRelayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (elementToBeCloned As TcpRelayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TcpRelayTransportBindingElement : Microsoft.ServiceBus.TcpRelayTransportBindingElement -&gt; Microsoft.ServiceBus.TcpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.TcpRelayTransportBindingElement elementToBeCloned" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToBeCloned" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToBeCloned">Das Element, geklont zu werden.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" /> -Klasse mit dem angegebenen Relay-Bindungselement. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="tcpRelayTransportBindingElement.BuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"> Der Typ der Kanalfactory. </typeparam>
        <param name="context"> Beschreibt die Bindungen, Verhaltensweisen, Verträge und andere Informationen zum Erstellen der Kanalfactory erforderlich sind.</param>
        <summary>Erstellt eine Kanalfactory, mit der ein Kanal erstellt werden kann.</summary>
        <returns>Eine Kanalfactory des angegebenen Typs.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"> Beim Transport-Schutz aktiviert ist und den Verbindungsmodus Satz an Hybrid oder Direct.This Member wahrscheinlich nicht direkt verwendet werden, jedoch dürfen beim Erstellen einer benutzerdefinierten Bindung verwendet werden. Weitere Informationen finden Sie unter Erstellen einer benutzerdefinierten AppFabric Service Bus-Bindungen.</exception>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="tcpRelayTransportBindingElement.BuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"> Der Typ der Kanalfactory. </typeparam>
        <param name="context"> Beschreibt die Bindungen, Verhaltensweisen, Verträge und andere Informationen zum Erstellen der Kanalfactory erforderlich sind.</param>
        <summary>Erstellt einen Kanallistener des angegebenen Typs.</summary>
        <returns>Ein Kanallistener des angegebenen Typs.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"> Wenn transportschutz aktiviert ist, und den Verbindungsmodus auf Hybrid oder direkt festgelegt wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="tcpRelayTransportBindingElement.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine Kopie des aktuellen Bindungselements.</summary>
        <returns>Gibt eine <see cref="T:System.ServiceModel.Channels.BindingElement" /> , die eine Kopie des Bindungselements enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Verbindungsmodus.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> , die den Verbindungsmodus enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPoolSettings As SocketConnectionPoolSettings" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.SocketConnectionPoolSettings" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketConnectionPoolSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Verbindung-Einstellungen für die aktuelle Instanz ab.</summary>
        <value>Die verbindungspooleinstellungen für die aktuelle Instanz.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="tcpRelayTransportBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T"> Der Typ des abzurufenden Objekts. </typeparam>
        <param name="context"> Der Kontext. </param>
        <summary>Gibt ein angegebenes Objekt aus dem Bindungskontext.</summary>
        <returns>Ein Bindungselement, das das angegebene Objekt oder Null enthält, wenn es nicht gefunden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob das Bindungselement, das dynamisch ist.</summary>
        <value>"true", wenn das Bindungselement, das dynamisch ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Typ der Authentifizierung verwendet, die für den Dienstclient fest.</summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />. Enthält den Authentifizierungstyp an. Der Standardwert ist RelayAccessToken.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.Scheme" />
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
        <value>Gibt das URI-Schema für den Transport "TCP" zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportPolicy (exporter As MetadataExporter, context As PolicyConversionContext) Implements IPolicyExportExtension.ExportPolicy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.MetadataExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.PolicyConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">Die MetadataExporter, die Sie zum Ändern des Exportprozesses verwenden können.</param>
        <param name="context">Die PolicyConversionContext, die Sie zum Einfügen einer benutzerdefinierten Richtlinienassertion verwenden können.</param>
        <summary>
            Exportiert eine benutzerdefinierte Richtlinienassertion über diese Bindung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>