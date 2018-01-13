<Type Name="ConnectionOrientedTransportBindingElement" FullName="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement">
  <TypeSignature Language="C#" Value="public abstract class ConnectionOrientedTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConnectionOrientedTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConnectionOrientedTransportBindingElement&#xA;Inherits TransportBindingElement" />
  <TypeSignature Language="F#" Value="type ConnectionOrientedTransportBindingElement = class&#xA;    inherit TransportBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Eine abstrakte Klasse, die das Basis-<see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> um zusätzliche Eigenschaften erweitert, die häufig bei verbindungsorientierten Transporten, z.&amp;#160;B. TCP und Named Pipes, verwendet werden.  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="connectionOrientedTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"></typeparam>
        <param name="context">BindingContext für den Kanal.</param>
        <summary>
            Bestimmt, ob eine Kanalfactory des angegebenen Typs erstellt werden kann.
            </summary>
        <returns>True, wenn IChannelListener&lt;TChannel&gt; des Typs IChannel kann durch das Bindungselement erstellt wurde, andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="connectionOrientedTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
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
        <typeparam name="TChannel"></typeparam>
        <param name="context">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</param>
        <summary>
            Gibt einen Wert zurück, der angibt, ob das Bindungselement einen Listener für einen bestimmten Typ von Kanal erstellen kann.
            </summary>
        <returns>True, wenn IChannelListener&lt;TChannel&gt; des Typs IChannel kann durch das Bindungselement erstellt wurde, andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Zeitspanne fest, die angibt, wie lange der kanalinitialisierung muss, bevor ein Timeout eintritt.</summary>
        <value>Gibt eine <see cref="T:System.TimeSpan" /> nach dem Timeout der Initialisierung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt und definiert die Größe des Puffers zum Übertragen eines Teils der serialisierten Nachricht über das Netzwerk vom Client oder Dienst verwendet. </summary>
        <value>Die Größe des Verbindungspuffers. Der Standardwert ist 8192 Bytes.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kleiner als 0 (null).</exception>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="connectionOrientedTransportBindingElement.GetProperty context" />
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
        <typeparam name="T">To be added.</typeparam>
        <param name="context">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</param>
        <summary>
            Ruft Eigenschaften vom bindungsstapel, ab, falls vorhanden.
            </summary>
        <returns>Ein Objekt des bindungsstapels, falls vorhanden, oder null, wenn nicht gefunden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Hostname zum Erreichen des Diensts bei übereinstimmendem URI verwendet werden soll.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.HostNameComparisonMode" /> , der bestimmt, ob der Hostname zum Erreichen des Diensts verwendet wird. Der Standardwert ist StrongWildCard, wodurch der Hostname und Port-Nummer im Vergleich ignoriert.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist eine gültige HostnameComparisonMode. </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Größe des zu verwendenden Puffers ab oder legt diese fest.</summary>
        <value>Die maximale Anzahl an Bytes, die verwendet wird, um eingehende Nachrichten im Arbeitsspeicher zu puffern. Der Standardwert ist 65.536 Bytes.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kleiner als oder gleich 0&amp;#160;(null).</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das maximale Zeitintervall ab, oder legt das maximale Zeitintervall fest, das als Teil einer Nachricht oder als vollständige Nachricht im Arbeitsspeicher gepuffert bleiben kann, bevor sie versendet wird.</summary>
        <value>Gibt eine <see cref="T:System.TimeSpan" /> , der angibt, dass des maximale Zeitintervall, das als Teil einer Nachricht oder vollständigen Meldung im Arbeitsspeicher gepuffert bleiben kann, bevor Sie versendet wird. Der Standardwert beträgt 2 Sekunden. Diese Eigenschaft ist nur sinnvoll, wenn die Eigenschaft AllowedOutputBatching einer ausgehenden Nachricht festgelegt ist auf "true". Andernfalls wird dieser Wert ignoriert, und die Nachrichten werden sofort gesendet.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kleiner als 0 (null).</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Anzahl ausstehender asynchroner Annahmevorgänge ab, die für die Verarbeitung beim Dienst eingehender Verbindungen zur Verfügung stehen, oder legt die maximale Anzahl fest.</summary>
        <value>Die maximale Anzahl an Verbindungen, die der Dienst gleichzeitig annehmen kann. Der Standardwert ist 1.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kleiner als oder gleich 0&amp;#160;(null).</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Anzahl an Verbindungen ab, die zum Verteilen auf dem Dienst bereitstehen, oder legt sie fest.</summary>
        <value>Die maximale Anzahl eingehender und am Dienst zur Verteilung bereitstehender Verbindungen. Der Standardwert ist 10.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kleiner als oder gleich 0&amp;#160;(null).</exception>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Meldungen bei verbindungsorientiertem Transport gepuffert oder per Stream übertragen werden.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> Streaming- oder Puffermodus für die nachrichtenübertragung gibt an, ob ein Kanal verwendet. Der Standardwert ist Buffered.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist eine gültige Übertragungsmodus.</exception>
      </Docs>
    </Member>
  </Members>
</Type>