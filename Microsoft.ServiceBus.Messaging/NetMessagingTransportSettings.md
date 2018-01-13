<Type Name="NetMessagingTransportSettings" FullName="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportSettings" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportSettings = class&#xA;    interface ITransportSettings&#xA;    interface IServiceBusSecuritySettings" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die .NET messaging transporteinstellungen dar.</summary>
    <remarks>
            Diese Klasse bietet Unterstützung für die spezifische Konfiguration Net Messaging Protocol (SBMP) für die NetMessagingBinding.MessagingFactorySettings-Eigenschaft.  
            Macht zur Konfiguration der Einstellungen, die auf die MessagingFactorySettings zur Verfügung stehen.
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
    <example>
      <code>
            Erstellen von Einstellungen für die MessagingFactory (für laufzeitvorgänge) MessagingFactorySettings FactorySettings neue MessagingFactorySettings() = {NetMessagingTransportSettings = neue NetMessagingTransportSettings(), Anmeldeinformationen = TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName, IssuerKey)};
            
            Erstellen der Factory MessagingFactory MessagingFactory = MessagingFactory.Create (MyServiceBusNamespace, FactorySettings);
            
            Anwendungswarteschlangen-Client erstellen
            
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public TimeSpan BatchFlushInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die batchleerungsintervall.</summary>
        <value>Batchleerungsintervall.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="netMessagingTransportSettings.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ITransportSettings.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine tiefe Kopie dieses Objekts.</summary>
        <returns>Eine Kopie dieses Objekts.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRedirect">
      <MemberSignature Language="C#" Value="public bool EnableRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.EnableRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableRedirect : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.EnableRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der angibt, ob die Nachricht Umleitung aktiviert ist.</summary>
        <value>"true", wenn die Nachricht Umleitung aktiviert ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.LeaseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Lease-Timeoutwert für die Eigenschaft LeaseTimeout innerhalb der <seealso cref="P:System.ServiceModel.Channels.TcpTransportBindingElement.ConnectionPoolSettings" /> Klasse.
            Die Standardeinstellung ist 5 Minuten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Lösen Sie aus, wenn der Wert kleiner sein als TimeSpan.Zero oder größer als Int32.MaxValue-Millisekunden ist.</exception>
      </Docs>
    </Member>
  </Members>
</Type>