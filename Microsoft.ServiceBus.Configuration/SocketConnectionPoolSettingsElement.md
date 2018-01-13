<Type Name="SocketConnectionPoolSettingsElement" FullName="Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement">
  <TypeSignature Language="C#" Value="public sealed class SocketConnectionPoolSettingsElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SocketConnectionPoolSettingsElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SocketConnectionPoolSettingsElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type SocketConnectionPoolSettingsElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt ein Konfigurationselement dar, das zusätzliche Verbindungspooleinstellungen für einen TCP-Transport angibt. Diese Klasse kann nicht vererbt werden.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SocketConnectionPoolSettingsElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("groupName", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Namen des Verbindungspools für ausgehende Kanäle verwendet.</summary>
        <value>Gibt den Namen des Verbindungspools für ausgehende Kanäle verwendet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan IdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan IdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.IdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.IdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.IdleTimeout" />
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
          <AttributeName>System.Configuration.ConfigurationProperty("idleTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Zeit, die die Verbindung im Leerlauf befinden kann, bevor Sie unterbrochen wird.</summary>
        <value>Gibt einen positiven <see cref="T:System.TimeSpan" /> , die die maximale Zeit angibt, die die Verbindung im Leerlauf befinden kann, bevor Sie unterbrochen wird. Der Standardwert ist 00:02:00.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.LeaseTimeout" />
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
          <AttributeName>System.Configuration.ConfigurationProperty("leaseTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Zeit ab oder legt die Zeit fest, nach der eine aktive Verbindung geschlossen wird.</summary>
        <value>Gibt eine <see cref="T:System.TimeSpan" /> , die er zeigt die Dauer, nach der die TCP-Verbindung geschlossen wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutboundConnectionsPerEndpoint">
      <MemberSignature Language="C#" Value="public int MaxOutboundConnectionsPerEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxOutboundConnectionsPerEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.MaxOutboundConnectionsPerEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutboundConnectionsPerEndpoint As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxOutboundConnectionsPerEndpoint : int with get, set" Usage="Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.MaxOutboundConnectionsPerEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxOutboundConnectionsPerEndpoint", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Anzahl von Verbindungen zu einem Remoteendpunkt ab oder legt die Verbindungen fest, die vom Dienst initiiert werden.</summary>
        <value>Gibt die maximale Anzahl von Verbindungen zu einem Remoteendpunkt, die vom Dienst initiiert werden. Der Standard ist 10.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Auflistung von Eigenschaften ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>