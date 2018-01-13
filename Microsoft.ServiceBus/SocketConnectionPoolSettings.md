<Type Name="SocketConnectionPoolSettings" FullName="Microsoft.ServiceBus.SocketConnectionPoolSettings">
  <TypeSignature Language="C#" Value="public sealed class SocketConnectionPoolSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SocketConnectionPoolSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SocketConnectionPoolSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SocketConnectionPoolSettings" />
  <TypeSignature Language="F#" Value="type SocketConnectionPoolSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Eigenschaften, die das Verhalten des Socket-Verbindungspools steuern.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Gruppennamen des Verbindungspools Socket.</summary>
        <value>Der Gruppenname des Verbindungspools Socket.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan IdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan IdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.IdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.IdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.IdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Zeit ab oder legt die maximale Zeit fest, in der sich eine Verbindung im Verbindungspool im Leerlauf befinden kann, bevor sie unterbrochen wird.</summary>
        <value>Die maximale Zeit kann die Verbindung im Leerlauf im Verbindungspool werden bevor Sie unterbrochen wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.LeaseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Zeit ab oder legt die Zeit fest, nach der eine aktive Verbindung geschlossen wird.</summary>
        <value>Die Dauer, nach der die Socketverbindung geschlossen wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutboundConnectionsPerEndpoint">
      <MemberSignature Language="C#" Value="public int MaxOutboundConnectionsPerEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxOutboundConnectionsPerEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SocketConnectionPoolSettings.MaxOutboundConnectionsPerEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutboundConnectionsPerEndpoint As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxOutboundConnectionsPerEndpoint : int with get, set" Usage="Microsoft.ServiceBus.SocketConnectionPoolSettings.MaxOutboundConnectionsPerEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Anzahl von ausgehenden Verbindungen für jeden Endpunkt ab, der im Verbindungspool zwischengespeichert wird, oder legt diese Anzahl fest.</summary>
        <value>Die maximale Anzahl von ausgehenden Verbindungen für jeden Endpunkt, der im Verbindungspool zwischengespeichert wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>