<Type Name="TransportFallbackType" FullName="Microsoft.Azure.Devices.Shared.TransportFallbackType">
  <TypeSignature Language="C#" Value="public enum TransportFallbackType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransportFallbackType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.TransportFallbackType" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransportFallbackType" />
  <TypeSignature Language="F#" Value="type TransportFallbackType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="67208-101">Definiert die fallen Back Transporttypen für AMQP und MQTT an.</span><span class="sxs-lookup"><span data-stu-id="67208-101">Defines the transport fall-back types for AMQP and MQTT.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TcpOnly">
      <MemberSignature Language="C#" Value="TcpOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Shared.TransportFallbackType TcpOnly = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Shared.TransportFallbackType.TcpOnly" />
      <MemberSignature Language="VB.NET" Value="TcpOnly" />
      <MemberSignature Language="F#" Value="TcpOnly = 2" Usage="Microsoft.Azure.Devices.Shared.TransportFallbackType.TcpOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.TransportFallbackType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="67208-102">Nur TCP-Verbindung mit keine fallen-zurück.</span><span class="sxs-lookup"><span data-stu-id="67208-102">Tcp only connection with no fall-back.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TcpWithWebSocketFallback">
      <MemberSignature Language="C#" Value="TcpWithWebSocketFallback" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Shared.TransportFallbackType TcpWithWebSocketFallback = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Shared.TransportFallbackType.TcpWithWebSocketFallback" />
      <MemberSignature Language="VB.NET" Value="TcpWithWebSocketFallback" />
      <MemberSignature Language="F#" Value="TcpWithWebSocketFallback = 0" Usage="Microsoft.Azure.Devices.Shared.TransportFallbackType.TcpWithWebSocketFallback" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.TransportFallbackType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="67208-103">Der Transport wird fallen-zum entsprechenden Websocket zurück, wenn Tcp-Verbindung ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="67208-103">The transport will fall-back to corresponding websocket if tcp connection fails.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="WebSocketOnly">
      <MemberSignature Language="C#" Value="WebSocketOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Shared.TransportFallbackType WebSocketOnly = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Shared.TransportFallbackType.WebSocketOnly" />
      <MemberSignature Language="VB.NET" Value="WebSocketOnly" />
      <MemberSignature Language="F#" Value="WebSocketOnly = 1" Usage="Microsoft.Azure.Devices.Shared.TransportFallbackType.WebSocketOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.TransportFallbackType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="67208-104">Nur WebSocket-Verbindung mit keine fallen-zurück.</span><span class="sxs-lookup"><span data-stu-id="67208-104">WebSocket only connection with no fall-back.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>