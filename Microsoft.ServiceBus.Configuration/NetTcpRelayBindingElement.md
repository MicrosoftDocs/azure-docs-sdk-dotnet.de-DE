<Type Name="NetTcpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class NetTcpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetTcpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class NetTcpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Konfigurationselement, das eine sichere, zuverlässige Bindung, die geeignet ist, für die computerübergreifende Kommunikation über das Azure Service Bus-Relay beschreibt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Konfigurationsname der Bindung.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />-Klasse mit einem angegebenen Konfigurationsnamen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ dieses Konfigurationselements ab. (Überschreibt StandardBindingElement.BindingElementType.)</summary>
        <value>Gibt eine <see cref="T:System.Type" /> , den Konfigurationselementtyp enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Verbindungsmodus in der Datei "App.config" für diese Konfiguration gespeichert.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> , enthält den Verbindungsmodus der Standardwert wird mittels Relay weitergeleitet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> Die Bindung nicht initialisieren.</param>
        <summary>Initialisiert den Inhalt dieses Bindungskonfigurationselements aus den Eigenschaftswerten einer angegebenen Bindung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("isDynamic", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("listenBacklog", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert fest, in der Datei "App.config", die die maximale Anzahl an Kanälen angibt, die akzeptiert werden auf dem Listener warten können.</summary>
        <value>Gibt die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange zurück. Der Standard ist 10.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferPoolSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Größe für einen Pufferpool enthält, die von der Bindung verarbeitet TCP-Nachrichten gespeichert werden.</summary>
        <value>Gibt zulässige die maximale Größe für einen Pufferpool, der von der Bindung verarbeitet Nachrichten gespeichert werden. Der Standardwert ist 65.536 Bytes.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Größe des Puffers zum Speichern von Nachrichten im Arbeitsspeicher in Bytes angibt.</summary>
        <value>Die maximale Größe (in Byte) des Puffers, der verwendet wird, um Meldungen im Arbeitsspeicher zu speichern.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Anzahl ausgehender und eingehender Verbindungen angibt, der Dienst erstellt bzw. annimmt.</summary>
        <value>Auf dem Client gibt die maximale Anzahl an Verbindungen, für die nachfolgende Wiederverwendung "zusammengelegt" werden; auf dem Server gibt Sie die maximale Anzahl zulässiger Verbindungen mit "Ausstehend" Verteilung zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxReceivedMessageSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert aus der Datei "App.config", die die maximale Größe einer Nachricht enthält, die in einem mit dieser Bindung konfigurierten Kanal empfangen werden können.</summary>
        <value>Gibt die maximale Größe in Byte für eine Nachricht, die von der Bindung verarbeitet wird zurück. Der Standardwert ist 65.536 Bytes.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"> Die Bindung, die Einstellungen zu aktualisieren.</param>
        <summary>Die Einstellungen dieses Konfigurationselements auf das angegebene Bindungselement angewendet.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft eine ConfigurationPropertyCollection-Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält. (Überschreibt StandardBindingElement.Properties.)</summary>
        <value>Eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("readerQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert aus der Datei "App.config", die Beschränkungen der Komplexität von SOAP-Nachrichten setzt, die von mit dieser Bindung konfigurierten Endpunkten verarbeitet werden können.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> , das die komplexitätseinschränkungen für ausgetauschte SOAP-Nachrichten angibt. Die Standardwerte für diese Einschränkungen werden im folgenden Hinweisabschnitt angegeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As StandardBindingOptionalReliableSessionElement" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("reliableSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ein Konfigurationselement ab, das angibt, ob zuverlässige Sitzungen zwischen Kanalendpunkten erstellt werden.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> , der angibt, ob eine zuverlässige WS-RM-Sitzung zwischen kanalendpunkten eingerichtet wird. Der Standardwert ist „false“.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetTcpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert aus der Datei "App.config", die bestimmt, der den Sicherheitstyp mit dieser Bindung verwendet werden soll.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> , das die Sicherheitseinstellungen für die zugeordnete Bindung enthält. Der Standardwert ist none. Die <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> abrufen aus der zugehörigen Bindung wird indirekt erstellt, mit einem NetTcpRelayBinding. Daher nach der Erstellung der Bindungsnamens können nicht Sie dieses Objekt durch ein neues Objekt ersetzen, wenn Sie auch eine neue Bindung erstellen. Allerdings können viele Elemente der WebHttpRelaySecurity über Sicherheitseigenschaft festgelegt werden. Weitere Informationen zur bindungssicherheit finden Sie unter im Abschnitt Sicherheit und Schutz. Zusammen mit dem Typ von Transport und Codierung stellen die Sicherheitseinstellungen für eine der drei wichtigsten Eigenschaften, die dieser Bindung zu definieren.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transferMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert aus der Datei "App.config", der angibt, ob Nachrichten gepuffert oder gestreamt werden oder eine Anforderung oder Antwort.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> enthält, die angibt, ob der Dienst mit der Bindung verwendet Streaming- oder Puffermodus (oder beides) nachrichtenübertragung. Die möglichen Werte sind wie folgt: BufferedStreamedStreamedRequestStreamedResponseThe-Standardwert ist Buffered.Specifying <see cref="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" /> auf Streamed bedeutet StreamedRequest und StreamedResponse.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>