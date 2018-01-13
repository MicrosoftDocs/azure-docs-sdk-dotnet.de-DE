<Type Name="IEventProcessorFactory" FullName="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory">
  <TypeSignature Language="C#" Value="public interface IEventProcessorFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessorFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessorFactory" />
  <TypeSignature Language="F#" Value="type IEventProcessorFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Schnittstelle, die von einem Ereignis Prozessor Formularbereichsfactory-Klasse implementiert werden muss.
            
            <para>Vom Benutzer bereitgestellte Factorys sind erforderlich, wenn mehr als nur ein neues mit einen parameterlosen Konstruktor arbeiten erstellen eine ereignisprozessorobjekt benötigt werden.</para></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateEventProcessor">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.Processor.IEventProcessor CreateEventProcessor (Microsoft.Azure.EventHubs.Processor.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.EventHubs.Processor.IEventProcessor CreateEventProcessor(class Microsoft.Azure.EventHubs.Processor.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory.CreateEventProcessor(Microsoft.Azure.EventHubs.Processor.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventProcessor (context As PartitionContext) As IEventProcessor" />
      <MemberSignature Language="F#" Value="abstract member CreateEventProcessor : Microsoft.Azure.EventHubs.Processor.PartitionContext -&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor" Usage="iEventProcessorFactory.CreateEventProcessor context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.IEventProcessor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context">Partition-Kontextinformationen.</param>
        <summary>
            Methode zum Erstellen der Instanz von <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> eine Partition erhält.
            </summary>
        <returns>Eine Instanz von <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>