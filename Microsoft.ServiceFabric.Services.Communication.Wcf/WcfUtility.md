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
            <span data-ttu-id="98819-101">Die Hilfsklasse zum Erstellen von standardbindungen für WCF-Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="98819-101">Utility class for creating default bindings for WCF communication.</span></span>
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
                <span data-ttu-id="98819-102">Maximale Größe der Nachricht in Bytes.</span><span class="sxs-lookup"><span data-stu-id="98819-102">Maximum size of the message in bytes.</span></span> <span data-ttu-id="98819-103">Wenn kein Wert angegeben ist, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="98819-103">If the value is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </param>
        <param name="openTimeout">
                <span data-ttu-id="98819-104">Timeout für das Öffnen der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="98819-104">Timeout for opening the connection.</span></span> <span data-ttu-id="98819-105">Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="98819-105">If the value is not specified, the default value of 5 seconds is used.</span></span>
                </param>
        <param name="closeTimeout">
                <span data-ttu-id="98819-106">Zeit zum Warten von Nachrichten auf den Verbindungen Ausgleich, bevor die Verbindung abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="98819-106">Time to wait for messages to drain on the connections before aborting the connection.</span></span> <span data-ttu-id="98819-107">Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="98819-107">If the value is not specified, the default value of 5 seconds is used.</span></span>
                </param>
        <summary>
                <span data-ttu-id="98819-108">Erstellt einen TCP-Client-Bindung ohne Sicherheit für WCF-Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="98819-108">Creates a TCP client binding with no security for WCF communication.</span></span>
            </summary>
        <returns><span data-ttu-id="98819-109">Eine <see cref="T:System.ServiceModel.Channels.Binding" />, die mit <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" /> verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="98819-109">A <see cref="T:System.ServiceModel.Channels.Binding" /> to use with <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />.</span></span></returns>
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
                <span data-ttu-id="98819-110">Maximale Größe der Nachricht in Bytes.</span><span class="sxs-lookup"><span data-stu-id="98819-110">Maximum size of the message in bytes.</span></span> <span data-ttu-id="98819-111">Wenn kein Wert angegeben ist, oder es ist kleiner als oder gleich 0 (null), einen Standardwert von 4,194,304 Bytes (4 MB) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="98819-111">If the value is not specified or it is less than or equals to zero, a default value of 4,194,304 bytes (4 MB) is used.</span></span>
                </param>
        <param name="openTimeout">
                <span data-ttu-id="98819-112">Timeout für das Öffnen der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="98819-112">Timeout for opening the connection.</span></span> <span data-ttu-id="98819-113">Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="98819-113">If the value is not specified, the default value of 5 seconds is used.</span></span>
                </param>
        <param name="closeTimeout">
                <span data-ttu-id="98819-114">Zeit zum Warten von Nachrichten auf den Verbindungen Ausgleich, bevor die Verbindung abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="98819-114">Time to wait for messages to drain on the connections before aborting the connection.</span></span> <span data-ttu-id="98819-115">Wenn kein Wert angegeben ist, wird der Standardwert von 5 Sekunden verwendet.</span><span class="sxs-lookup"><span data-stu-id="98819-115">If the value is not specified, the default value of 5 seconds is used.</span></span>
                </param>
        <summary>
                <span data-ttu-id="98819-116">Erstellt einen TCP-Listener-Bindung ohne Sicherheit für WCF-Kommunikation an.</span><span class="sxs-lookup"><span data-stu-id="98819-116">Creates a TCP listener binding with no security for WCF communication.</span></span>
            </summary>
        <returns><span data-ttu-id="98819-117">Eine <see cref="T:System.ServiceModel.Channels.Binding" />, die mit <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" /> verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="98819-117">A <see cref="T:System.ServiceModel.Channels.Binding" /> to use with <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>