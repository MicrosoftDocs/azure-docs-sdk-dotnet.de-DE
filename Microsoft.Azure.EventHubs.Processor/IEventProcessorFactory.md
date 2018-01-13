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
            <span data-ttu-id="fed3a-101">Schnittstelle, die von einem Ereignis Prozessor Formularbereichsfactory-Klasse implementiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="fed3a-101">Interface that must be implemented by an event processor factory class.</span></span>
            
            <span data-ttu-id="fed3a-102"><para>Vom Benutzer bereitgestellte Factorys sind erforderlich, wenn mehr als nur ein neues mit einen parameterlosen Konstruktor arbeiten erstellen eine ereignisprozessorobjekt benötigt werden.</para></span><span class="sxs-lookup"><span data-stu-id="fed3a-102"><para>User-provided factories are needed if creating an event processor object requires more work than just a new with a parameterless constructor.</para></span></span></summary>
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
        <param name="context"><span data-ttu-id="fed3a-103">Partition-Kontextinformationen.</span><span class="sxs-lookup"><span data-stu-id="fed3a-103">Partition context information.</span></span></param>
        <summary>
            <span data-ttu-id="fed3a-104">Methode zum Erstellen der Instanz von <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> eine Partition erhält.</span><span class="sxs-lookup"><span data-stu-id="fed3a-104">Method to create instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> given a partition.</span></span>
            </summary>
        <returns><span data-ttu-id="fed3a-105">Eine Instanz von <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="fed3a-105">An instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>