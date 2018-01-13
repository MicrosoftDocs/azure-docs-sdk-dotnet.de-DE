<Type Name="NetMessagingTransportBindingElement" FullName="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement, System.ServiceModel.Description.IPolicyExportExtension, System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement implements class System.ServiceModel.Description.IPolicyExportExtension, class System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportBindingElement&#xA;Inherits TransportBindingElement&#xA;Implements IPolicyExportExtension, IWsdlExportExtension" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportBindingElement = class&#xA;    inherit TransportBindingElement&#xA;    interface IPolicyExportExtension&#xA;    interface IWsdlExportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IWsdlExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Stellt das Bindungselement, das zum Angeben einer Netzes-Übertragung zum Senden von Nachrichten auf dem Service Bus messaging verwendet.</summary>
    <remarks>
            Die NetMessagingTransportBindingElement unterstützt erstellen IOutputChannel, IInputChannel, IInputChannel + ReceiveContext, IInputSessionChannel und IInputSessionChannel + ReceiveContext. Die sitzungsfähigen Kanälen (IInputSessionChannel, IInputSessionChannel + ReceiveContext) dienen der sitzungsunterstützung.
             </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="netMessagingTransportBindingElement.BuildChannelFactory context" />
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
        <typeparam name="TChannel"> Der Typ des Kanals. </typeparam>
        <param name="context"> Der Bindungskontext. </param>
        <summary> Erstellt eine Kanalfactory erstellt werden. </summary>
        <returns> Die Schnittstelle implementiert, die von der Kanalfactory. </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die TChannel-Eigenschaft ist eine unterstützte Kanaltyp nicht </exception>
        <exception cref="T:System.ArgumentNullException"> Wird ausgelöst, wenn Kontext null ist. </exception>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="netMessagingTransportBindingElement.BuildChannelListener context" />
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
        <typeparam name="TChannel"> Der Typ des Kanals. </typeparam>
        <param name="context"> Der Bindungskontext. </param>
        <summary> Erstellt einen Kanallistener. </summary>
        <returns> Eine implementierte IChannelListener-Schnittstelle. </returns>
        <remarks>
                     Kanallistener und ihre zugeordneten Kanäle werden im Allgemeinen von Diensten verwendet, die von Clients initiierte Kommunikationen empfangen. Kanalfactorys, die die Schnittstelle IChannelFactory implementieren, bieten, im Gegensatz dazu die Mechanismen verwendet, um die Kanäle erstellen, die über die Kommunikation mit einem Dienst initiiert wird. </remarks>
        <exception cref="T:System.ArgumentNullException"> Wird ausgelöst, wenn Kontext null ist. </exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die TChannel-Eigenschaft ist eine unterstützte Kanaltyp nicht </exception>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelFactory&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;T&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of T) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="netMessagingTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T"> Der Typ des Kanals. </typeparam>
        <param name="context"> Der Bindungskontext. </param>
        <summary> Abfragen kann die Kanalfactory "Context" erstellen. </summary>
        <returns> Gibt einen Wert zurück, der angibt, ob das Bindungselement eine Kanalfactory für einen bestimmten Typ von Kanälen erstellen kann. </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> Wird ausgelöst, wenn Argument ist null. </exception>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of T As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'T : null and 'T :&gt; System.ServiceModel.Channels.IChannel)" Usage="netMessagingTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
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
        <typeparam name="T"> Generische Typparameter. </typeparam>
        <param name="context"> Der Bindungskontext. </param>
        <summary> Abfragen, wenn der Kanallistener 'Context' erstellt werden kann. </summary>
        <returns> Gibt einen Wert, der angibt, ob das Bindungselement, das einen Kanallistener für einen bestimmten Typ von Kanal erstellen kann. </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> Wird ausgelöst, wenn Argument ist null. </exception>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="netMessagingTransportBindingElement.Clone " />
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
        <summary>Erstellt eine tiefe Kopie dieses Bindungselements.</summary>
        <returns>Eine Kopie dieses Bindungselements.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="netMessagingTransportBindingElement.GetProperty context" />
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
        <typeparam name="T"> Generische Typparameter. </typeparam>
        <param name="context"> Der Bindungskontext. </param>
        <summary> Ruft eine bestimmte Bindung-Element-Eigenschaft ab. </summary>
        <returns> Die T-Eigenschaft </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Argument ist null. </exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(-1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Prefetch.</summary>
        <value>Die Anzahl der Prefetch.</value>
        <remarks> Wirkt sich auf die nächste empfangsaufruf mit dem server </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.Scheme" />
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
        <value>Das URI-Schema für den Transport.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(typeof(System.TimeSpan), "00:01:00")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Timespan-Wert, der Zeitraum der Inaktivität angibt, die die Sitzung, bevor ein Timeout auftritt wartet.</summary>
        <value>Die Timespan-Wert. Der Standardwert beträgt 1 Minute.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
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
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportContract">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportContract (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlContractConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportContract(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlContractConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportContract (exporter As WsdlExporter, context As WsdlContractConversionContext) Implements IWsdlExportExtension.ExportContract" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlExportExtension.ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.WsdlExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlContractConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">To be added.</param>
        <param name="context">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportEndpoint (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlEndpointConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlEndpointConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportEndpoint (exporter As WsdlExporter, context As WsdlEndpointConversionContext) Implements IWsdlExportExtension.ExportEndpoint" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.WsdlExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlEndpointConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">To be added.</param>
        <param name="context">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportSettings As NetMessagingTransportSettings" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die transporteinstellungen für die net-messaging.</summary>
        <value>Die transporteinstellungen für die net-messaging.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>