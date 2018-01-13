<Type Name="WcfUtility" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility">
  <TypeSignature Language="C#" Value="public static class WcfUtility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed WcfUtility extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfUtility" />
  <TypeSignature Language="F#" Value="type WcfUtility = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Hilfsklasse zum Erstellen von standardbindungen für WCF-Kommunikation.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTcpClientBinding">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Binding CreateTcpClientBinding (long maxMessageSize = 4194304, TimeSpan openTimeout = null, TimeSpan closeTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Binding CreateTcpClientBinding(int64 maxMessageSize, valuetype System.TimeSpan openTimeout, valuetype System.TimeSpan closeTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTcpClientBinding (Optional maxMessageSize As Long = 4194304, Optional openTimeout As TimeSpan = null, Optional closeTimeout As TimeSpan = null) As Binding" />
      <MemberSignature Language="F#" Value="static member CreateTcpClientBinding : int64 * TimeSpan * TimeSpan -&gt; System.ServiceModel.Channels.Binding" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding (maxMessageSize, openTimeout, closeTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Binding</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageSize" Type="System.Int64" />
        <Parameter Name="openTimeout" Type="System.TimeSpan" />
        <Parameter Name="closeTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageSize">
                Maximale Größe der Nachricht in Bytes. Wenn kein Wert angegeben ist, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.
                </param>
        <param name="openTimeout">
                Timeout für das Öffnen der Verbindung. Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.
                </param>
        <param name="closeTimeout">
                Zeit zum Warten von Nachrichten auf den Verbindungen Ausgleich, bevor die Verbindung abgebrochen wird. Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.
                </param>
        <summary>
                Erstellt einen TCP-Client-Bindung ohne Sicherheit für WCF-Kommunikation.
            </summary>
        <returns>Eine <see cref="T:System.ServiceModel.Channels.Binding" />, die mit <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" /> verwendet wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTcpListenerBinding">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Binding CreateTcpListenerBinding (long maxMessageSize = 4194304, TimeSpan openTimeout = null, TimeSpan closeTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Binding CreateTcpListenerBinding(int64 maxMessageSize, valuetype System.TimeSpan openTimeout, valuetype System.TimeSpan closeTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTcpListenerBinding (Optional maxMessageSize As Long = 4194304, Optional openTimeout As TimeSpan = null, Optional closeTimeout As TimeSpan = null) As Binding" />
      <MemberSignature Language="F#" Value="static member CreateTcpListenerBinding : int64 * TimeSpan * TimeSpan -&gt; System.ServiceModel.Channels.Binding" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding (maxMessageSize, openTimeout, closeTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Binding</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageSize" Type="System.Int64" />
        <Parameter Name="openTimeout" Type="System.TimeSpan" />
        <Parameter Name="closeTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageSize">
                Maximale Größe der Nachricht in Bytes. Wenn kein Wert angegeben ist, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.
                </param>
        <param name="openTimeout">
                Timeout für das Öffnen der Verbindung. Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.
                </param>
        <param name="closeTimeout">
                Zeit zum Warten von Nachrichten auf den Verbindungen Ausgleich, bevor die Verbindung abgebrochen wird. Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.
                </param>
        <summary>
                Erstellt einen TCP-Listener-Bindung ohne Sicherheit für WCF-Kommunikation an.
            </summary>
        <returns>Eine <see cref="T:System.ServiceModel.Channels.Binding" />, die mit <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" /> verwendet wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>