<Type Name="DefaultEventProcessorFactory&lt;T&gt;" FullName="Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class DefaultEventProcessorFactory&lt;T&gt; : Microsoft.ServiceBus.Messaging.IEventProcessorFactory where T : IEventProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DefaultEventProcessorFactory`1&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt; extends System.Object implements class Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Class DefaultEventProcessorFactory(Of T)&#xA;Implements IEventProcessorFactory" />
  <TypeSignature Language="F#" Value="type DefaultEventProcessorFactory&lt;'T (requires 'T :&gt; IEventProcessor)&gt; = class&#xA;    interface IEventProcessorFactory" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessorFactory</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="71f62-101">Der Typ des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="71f62-101">The type of the event.</span></span></typeparam>
    <summary><span data-ttu-id="71f62-102">Stellt die Factory für den Standard-Ereignis-Prozessor dar.</span><span class="sxs-lookup"><span data-stu-id="71f62-102">Represents the factory for the default event processor.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DefaultEventProcessorFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="71f62-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="71f62-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DefaultEventProcessorFactory (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instance As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory&lt;'T (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)&gt; : 'T -&gt; Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory&lt;'T (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)&gt;" Usage="new Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory&lt;'T (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)&gt; instance" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance"><span data-ttu-id="71f62-104">Die Instanz.</span><span class="sxs-lookup"><span data-stu-id="71f62-104">The instance.</span></span></param>
        <summary><span data-ttu-id="71f62-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> -Klasse unter Verwendung der angegebenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="71f62-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> class using the specified instance.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventProcessor">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.IEventProcessor CreateEventProcessor (Microsoft.ServiceBus.Messaging.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.IEventProcessor CreateEventProcessor(class Microsoft.ServiceBus.Messaging.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1.CreateEventProcessor(Microsoft.ServiceBus.Messaging.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventProcessor (context As PartitionContext) As IEventProcessor" />
      <MemberSignature Language="F#" Value="abstract member CreateEventProcessor : Microsoft.ServiceBus.Messaging.PartitionContext -&gt; Microsoft.ServiceBus.Messaging.IEventProcessor&#xA;override this.CreateEventProcessor : Microsoft.ServiceBus.Messaging.PartitionContext -&gt; Microsoft.ServiceBus.Messaging.IEventProcessor" Usage="defaultEventProcessorFactory.CreateEventProcessor context" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IEventProcessorFactory.CreateEventProcessor(Microsoft.ServiceBus.Messaging.PartitionContext)</InterfaceMember>
      </Implements>
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
        <param name="context"><span data-ttu-id="71f62-106">Der Kontext Partition.</span><span class="sxs-lookup"><span data-stu-id="71f62-106">The partition context.</span></span></param>
        <summary><span data-ttu-id="71f62-107">Erstellt einen Ereignisprozessor.</span><span class="sxs-lookup"><span data-stu-id="71f62-107">Creates an event processor.</span></span></summary>
        <returns><span data-ttu-id="71f62-108">Der erstellte Ereignis-Prozessor.</span><span class="sxs-lookup"><span data-stu-id="71f62-108">The created event processor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>