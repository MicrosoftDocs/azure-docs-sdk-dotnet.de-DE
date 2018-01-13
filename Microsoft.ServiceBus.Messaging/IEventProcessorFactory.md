<Type Name="IEventProcessorFactory" FullName="Microsoft.ServiceBus.Messaging.IEventProcessorFactory">
  <TypeSignature Language="C#" Value="public interface IEventProcessorFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessorFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessorFactory" />
  <TypeSignature Language="F#" Value="type IEventProcessorFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>Eine Schnittstelle, die eine Factory zum Erstellen von Instanzen der bietet <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</summary>
    <remarks>Verwenden Sie ggf. eine weitere erweiterte Möglichkeit zum Erstellen eine Factory <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />. Andernfalls können Sie EventHubConsumerGroup.RegisterProcessor verwenden, nur den Prozessortyp Ereignis angeben.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateEventProcessor">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.IEventProcessor CreateEventProcessor (Microsoft.ServiceBus.Messaging.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.IEventProcessor CreateEventProcessor(class Microsoft.ServiceBus.Messaging.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessorFactory.CreateEventProcessor(Microsoft.ServiceBus.Messaging.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventProcessor (context As PartitionContext) As IEventProcessor" />
      <MemberSignature Language="F#" Value="abstract member CreateEventProcessor : Microsoft.ServiceBus.Messaging.PartitionContext -&gt; Microsoft.ServiceBus.Messaging.IEventProcessor" Usage="iEventProcessorFactory.CreateEventProcessor context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IEventProcessor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context">Partition-Kontextinformationen.</param>
        <summary>Erstellt eine neue Instanz der Ereignisprozessor in der angegebenen Partition.</summary>
        <returns>Eine Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>