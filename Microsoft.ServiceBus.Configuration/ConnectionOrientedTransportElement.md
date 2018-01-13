<Type Name="ConnectionOrientedTransportElement" FullName="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement">
  <TypeSignature Language="C#" Value="public abstract class ConnectionOrientedTransportElement : System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConnectionOrientedTransportElement extends System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConnectionOrientedTransportElement&#xA;Inherits TransportElement" />
  <TypeSignature Language="F#" Value="type ConnectionOrientedTransportElement = class&#xA;    inherit TransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.TransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt das Konfigurationselement dar, das verbindungsorientierten Transportbindungselementen, wie beispielsweise TCP und Named Pipes, zusätzliche Konfigurationseinstellungen bereitstellt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="connectionOrientedTransportElement.ApplyConfiguration bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement">Das Bindungselement, das die Einstellungen zu aktualisieren.</param>
        <summary>Wendet die Einstellungen dieses Konfigurationselements auf das angegebene <see cref="T:System.ServiceModel.Channels.BindingElement" /> an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("channelInitializationTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Zeit ab oder legt die maximale Zeit fest, in der sich der Kanal im Initialisierungsstatus befinden kann, bevor die Verbindung getrennt wird.</summary>
        <value>Die maximale Zeit, die der Kanal in den Initialisierungsstatus befinden kann, bevor Sie unterbrochen wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Puffergröße ab oder legt die Puffergröße fest, die zum Übertragen eines Teils der Meldung vom Client oder Dienst verwendet wird.</summary>
        <value>Gibt eine <see cref="T:System.Int32" /> , enthält die Größe des Puffers zum Übertragen eines Teils der serialisierten Nachricht über das Netzwerk vom Client oder Dienst verwendet. Der Standardwert ist 8 KB.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="connectionOrientedTransportElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from">Das zu kopierende Konfigurationselement.</param>
        <summary>Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("hostNameComparisonMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Hostname zum Erreichen des Diensts bei übereinstimmendem URI verwendet werden soll.</summary>
        <value>Ein gültiger HostnameComparisonMode-Wert, der angibt, ob der Hostname beim routing eingehender Anfragen an einen Endpunkt-URI eingeschlossen wird. Der Standardwert ist StrongWildcard, wodurch der Hostname beim Abgleich ignoriert wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxBufferSize" />
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
        <summary>Ruft die maximale Größe des zu verwendenden Puffers ab oder legt diese fest.</summary>
        <value>Die maximale Anzahl an Bytes, die verwendet wird, um eingehende Nachrichten im Arbeitsspeicher zu puffern. Der Standardwert ist 65.536 Bytes.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxOutputDelay", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das maximale Zeitintervall ab oder legt das maximale Zeitintervall fest, das als Teil einer Meldung oder vollständigen Meldung im Arbeitsspeicher gepuffert bleiben kann, bevor sie versendet wird.</summary>
        <value>Das maximale Zeitintervall, das als Teil einer Nachricht oder als vollständige Nachricht bleiben kann im Arbeitsspeicher gepuffert werden, bevor Sie versendet wird. Der Standardwert beträgt 2 Sekunden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxPendingAccepts", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Anzahl ausstehender asynchroner Annahmethreads ab, die für die Verarbeitung eingehender Verbindungen beim Dienst zur Verfügung stehen, oder legt die maximale Anzahl fest.</summary>
        <value>Die maximale Anzahl ausstehender Meldungen, die der Dienst annehmen kann. Der Standardwert ist 1.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxPendingConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Anzahl ausstehender Verbindungen ab oder legt sie fest.</summary>
        <value>Die maximale Anzahl ausstehender Verbindungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft eine ConfigurationPropertyCollection-Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</summary>
        <value>Gibt eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> Instanz, die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement dieses Konfigurationselements enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.TransferMode" />
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
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Meldungen bei verbindungsorientiertem Transport gepuffert oder per Stream übertragen werden.</summary>
        <value>Gibt eine gültige <see cref="T:System.ServiceModel.TransferMode" /> Wert, der angibt, ob ein Kanal verwendet den Stream- oder Puffermodus für die nachrichtenübertragung. Der Standardwert ist Buffered.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>