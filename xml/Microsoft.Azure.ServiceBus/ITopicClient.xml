<Type Name="ITopicClient" FullName="Microsoft.Azure.ServiceBus.ITopicClient">
  <TypeSignature Language="C#" Value="public interface ITopicClient : Microsoft.Azure.ServiceBus.Core.ISenderClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITopicClient implements class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ITopicClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITopicClient&#xA;Implements ISenderClient" />
  <TypeSignature Language="F#" Value="type ITopicClient = interface&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.ISenderClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="0a450-101">TopicClient kann für alle grundlegenden Interaktionen mit einem Service Bus-Thema verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0a450-101">TopicClient can be used for all basic interactions with a Service Bus topic.</span></span>
             </summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
            
             <span data-ttu-id="0a450-102">Erstellen Sie die TopicClient ITopicClient MyTopicClient = neue TopicClient (ServiceBusConnectionString, Name_des_themas);</span><span class="sxs-lookup"><span data-stu-id="0a450-102">// Create the TopicClient ITopicClient myTopicClient = new TopicClient( serviceBusConnectionString, topicName);</span></span>
             
                 <span data-ttu-id="0a450-103">/ / Senden von Nachrichten an ein Thema / / \*\*\*</span><span class="sxs-lookup"><span data-stu-id="0a450-103">//******************************************************************************** //                          Sending messages to a Topic //********************************************************************************</span></span>
                 
            <span data-ttu-id="0a450-104">Senden von Nachrichten Liste &lt;Byte []&gt; Probleme = GetIssues(); Foreach (Var Problem Punkte) {myTopicClient.SendAsync (neue Message(issue));}</span><span class="sxs-lookup"><span data-stu-id="0a450-104">// Send messages List &lt;byte[]&gt; Issues = GetIssues(); foreach (var issue in Issues) { myTopicClient.SendAsync(new Message(issue)); }</span></span>
             </code>
    </example>
    <example>
             <span data-ttu-id="0a450-105">Erstellen Sie eine neue TopicClient</span><span class="sxs-lookup"><span data-stu-id="0a450-105">Create a new TopicClient</span></span>
             <code>
             ITopicClient topicClient = new TopicClient(
                 namespaceConnectionString,
                 topicName,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="0a450-106">Senden einer Nachricht an das Thema:</span><span class="sxs-lookup"><span data-stu-id="0a450-106">Send a message to the topic:</span></span>
             <code>
             byte[] data = GetData();
             await topicClient.SendAsync(data);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="TopicName">
      <MemberSignature Language="C#" Value="public string TopicName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ITopicClient.TopicName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicName As String" />
      <MemberSignature Language="F#" Value="member this.TopicName : string" Usage="Microsoft.Azure.ServiceBus.ITopicClient.TopicName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a450-107">Ruft den Namen des Themas.</span><span class="sxs-lookup"><span data-stu-id="0a450-107">Gets the name of the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>