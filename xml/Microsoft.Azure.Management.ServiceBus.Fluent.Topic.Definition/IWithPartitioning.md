<Type Name="IWithPartitioning" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithPartitioning">
  <TypeSignature Language="C#" Value="public interface IWithPartitioning" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPartitioning" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithPartitioning" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPartitioning" />
  <TypeSignature Language="F#" Value="type IWithPartitioning = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f2c13-101">Die Phase der themadefinition ermöglicht die Partitionierung Verhalten angeben.</span><span class="sxs-lookup"><span data-stu-id="f2c13-101">The stage of the topic definition allowing to specify partitioning behaviour.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPartitioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithoutPartitioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithoutPartitioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithPartitioning.WithoutPartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPartitioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPartitioning : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithPartitioning.WithoutPartitioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2c13-102">Gibt an, dass die Standard-Partitionierung zu diesem Thema deaktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="f2c13-102">Specifies that the default partitioning should be disabled on this topic.</span></span>
            <span data-ttu-id="f2c13-103">Hinweis: Wenn das übergeordnete Element Service Bus Premium SKU ist kann dann Partition deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="f2c13-103">Note: if the parent Service Bus is Premium SKU then partition cannot be disabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f2c13-104">Die nächste Phase der themadefinition.</span><span class="sxs-lookup"><span data-stu-id="f2c13-104">The next stage of topic definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPartitioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithPartitioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithPartitioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithPartitioning.WithPartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPartitioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPartitioning : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithPartitioning.WithPartitioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2c13-105">Gibt an, dass zu diesem Thema Partitionierung aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="f2c13-105">Specifies that partitioning should be enabled on this topic.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f2c13-106">Die nächste Phase der themadefinition.</span><span class="sxs-lookup"><span data-stu-id="f2c13-106">The next stage of topic definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>