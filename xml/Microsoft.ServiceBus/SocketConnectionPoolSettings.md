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
    <summary><span data-ttu-id="67c57-101">Stellt die Eigenschaften, die das Verhalten des Socket-Verbindungspools steuern.</span><span class="sxs-lookup"><span data-stu-id="67c57-101">Represents the properties that control the behavior of the socket connection pool.</span></span></summary>
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
        <summary><span data-ttu-id="67c57-102">Ruft ab oder legt den Gruppennamen des Verbindungspools Socket.</span><span class="sxs-lookup"><span data-stu-id="67c57-102">Gets or sets the group name of the socket connection pool.</span></span></summary>
        <value><span data-ttu-id="67c57-103">Der Gruppenname des Verbindungspools Socket.</span><span class="sxs-lookup"><span data-stu-id="67c57-103">The group name of the socket connection pool.</span></span></value>
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
        <summary><span data-ttu-id="67c57-104">Ruft die maximale Zeit ab oder legt die maximale Zeit fest, in der sich eine Verbindung im Verbindungspool im Leerlauf befinden kann, bevor sie unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="67c57-104">Gets or sets the maximum time the connection can be idle in the connection pool before being disconnected.</span></span></summary>
        <value><span data-ttu-id="67c57-105">Die maximale Zeit kann die Verbindung im Leerlauf im Verbindungspool werden bevor Sie unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="67c57-105">The maximum time the connection can be idle in the connection pool before being disconnected.</span></span></value>
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
        <summary><span data-ttu-id="67c57-106">Ruft die Zeit ab oder legt die Zeit fest, nach der eine aktive Verbindung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="67c57-106">Gets or sets the time span after which an active connection is closed.</span></span></summary>
        <value><span data-ttu-id="67c57-107">Die Dauer, nach der die Socketverbindung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="67c57-107">The duration after which the socket connection is closed.</span></span></value>
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
        <summary><span data-ttu-id="67c57-108">Ruft die maximale Anzahl von ausgehenden Verbindungen für jeden Endpunkt ab, der im Verbindungspool zwischengespeichert wird, oder legt diese Anzahl fest.</span><span class="sxs-lookup"><span data-stu-id="67c57-108">Gets or sets the maximum number of outbound connections for each endpoint that is cached in the connection pool.</span></span></summary>
        <value><span data-ttu-id="67c57-109">Die maximale Anzahl von ausgehenden Verbindungen für jeden Endpunkt, der im Verbindungspool zwischengespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="67c57-109">The maximum number of outbound connections for each endpoint that is cached in the connection pool.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>