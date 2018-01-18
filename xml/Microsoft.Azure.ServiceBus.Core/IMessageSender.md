<Type Name="IMessageSender" FullName="Microsoft.Azure.ServiceBus.Core.IMessageSender">
  <TypeSignature Language="C#" Value="public interface IMessageSender : Microsoft.Azure.ServiceBus.Core.ISenderClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSender implements class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IMessageSender" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSender&#xA;Implements ISenderClient" />
  <TypeSignature Language="F#" Value="type IMessageSender = interface&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
             <span data-ttu-id="a8eeb-101">Die MessageSender kann verwendet werden, um das Senden von Nachrichten an Warteschlangen oder Themen.</span><span class="sxs-lookup"><span data-stu-id="a8eeb-101">The MessageSender can be used to send messages to Queues or Topics.</span></span>
             </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.TopicClient" />
    <example>
             <span data-ttu-id="a8eeb-102">Erstellen Sie eine neue MessageSender an eine Warteschlange senden</span><span class="sxs-lookup"><span data-stu-id="a8eeb-102">Create a new MessageSender to send to a Queue</span></span>
             <code>
             IMessageSender messageSender = new MessageSender(
                 namespaceConnectionString,
                 queueName)
             </code>
            
             <span data-ttu-id="a8eeb-103">Nachricht senden</span><span class="sxs-lookup"><span data-stu-id="a8eeb-103">Send message</span></span>
             <code>
             byte[] data = GetData();
             await messageSender.SendAsync(data);
             </code></example>
  </Docs>
  <Members />
</Type>