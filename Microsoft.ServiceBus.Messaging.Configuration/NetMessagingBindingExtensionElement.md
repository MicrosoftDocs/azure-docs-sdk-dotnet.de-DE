<Type Name="NetMessagingBindingExtensionElement" FullName="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingBindingExtensionElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingBindingExtensionElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingBindingExtensionElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetMessagingBindingExtensionElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt ein XML-Element, der angibt, eine Konfiguration des <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />.</summary>
    <remarks>
            Die NetMessagingBinding und NetMessagingTransportBindingElement können WCF-Clients auf einfache Weise senden und Empfangen von Nachrichten für Service Bus-Messagingentitäten (Warteschlangen, Themen und Abonnements).  
             Diesen Nachrichtenaustausch verwenden standard WCF-Programmiermodell, z. B. IOutputChannel, IInputChannel, IInputSessionChannel und ReceiveContext.  
            Die NetMessagingTransportBindingElement unterstützt erstellen IOutputChannel, IInputChannel, IInputChannel + ReceiveContext, IInputSessionChannel und IInputSessionChannel + ReceiveContext.  Die sitzungsbasierten Kanäle (IInputSessionChannel, IInputSessionChannel + ReceiveContext) dienen der Unterstützung der Sitzung/Konversation.
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBindingExtensionElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBindingExtensionElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement : string -&gt; Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" Usage="new Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" />-Klasse unter Verwendung des angegebenen Namens.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Bindungselements darstellt, die verwendet wird.
            </summary>
        <value> Der Typ des Bindungselements darstellt, die verwendet wird. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netMessagingBindingExtensionElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> Eine Bindung. </param>
        <summary> Initialisiert dieses Bindungskonfigurationselement mit dem Inhalt der angegebenen Bindung. </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="binding" /> ist NULL.
            </exception>
        <exception cref="T:System.ArgumentException">
            Der Typ dieses Bindungselements unterscheidet sich von dem durch <paramref name="binding" /> angegebenen Typ.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netMessagingBindingExtensionElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> Eine Bindung. </param>
        <summary> Wird aufgerufen, wenn der Inhalt eines angegebenen Bindungselements für dieses Bindungskonfigurationselement übernommen wird. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("prefetchCount", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
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
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> Ruft eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" />-Instanz ab, die eine Auflistung von <see cref="T:System.Configuration.ConfigurationProperty" />-Objekten enthält, die Attribute oder <see cref="T:System.Configuration.ConfigurationElement" />-Objekte dieses Konfigurationselements sein können. </summary>
        <value> Eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" />-Instanz, die eine Sammlung mit <see cref="T:System.Configuration.ConfigurationProperty" />-Objekten enthält, die entweder Attribute oder <see cref="T:System.Configuration.ConfigurationElement" />-Objekte dieses Konfigurationselements sein können. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sessionIdleTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.PositiveTimeSpanValidator</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die SessionIdleTimeout.</summary>
        <value>Wenn ein Vorgang IInputSessionChannel.TryReceive Meldung(en) innerhalb dieser Zeitspanne keine erhält, wird der Kanal Ende der Sitzung angegeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement TransportSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransportSettings As NetMessagingTransportSettingsElement" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transportSettings", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Transportbindungselement der Einstellungen für die net-messaging.</summary>
        <value>Das Transportelement des Einstellungen für die net-messaging.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>